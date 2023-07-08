# emacs_config

Instructions and files for setting up my emacs environment.

___

## Contents

`init.el` contains the core Emacs config.

`.gitconfig` and `.authinfo` should be edited to contain info necessary for ghub/magit/forge for communicating with github.

`app_shortcuts/` contains system scripts (that should be edited) that launch emacs itself (after setting appropriate path variables) and other applications that can be launched within emacs via `& <appname>` in dired/dirvish mode.

## Set up instructions

1. Download Emacs: https://alpha.gnu.org/gnu/emacs/pretest/
2. Move and add the `'app_shortcuts/'` dir to the system path.
3. Edit the emacs launcher script in `app_shortcuts` as necessary.
4. Move `.gitconfig`, and `.authinfo` to the location specified by 'HOME' in the emacs launcher script, and move `init.el` to an `.emacs.d/` directory within this 'HOME' location.
5. Launch emacs from the launcher script: voila.
