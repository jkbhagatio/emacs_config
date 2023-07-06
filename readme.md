# emacs_config

Instructions and files for setting up my emacs environment.

___

`init.el` contains the core Emacs config.

`app_shortcuts/` contains system scripts (that should be edited) that launch emacs itself (after setting appropriate path variables) and other applications that can be launched within emacs via `& <appname>` in dired/dirvish mode.

`.gitconfig` and `.authinfo` should be edited to contain info necessary for ghub/magit/forge for communicating with github.


## Known issues

- global command log mode isn't initialized on start-up even though it's set in `init.el`
