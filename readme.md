# emacs_config

Instructions and files for setting up my emacs environment.

___

`init.el` contains the core Emacs config.
`app_shortcuts/` should be edited to contain system scripts that launch applications, which can be launched via `& <appname>` in dired/dirvish mode.
`.gitconfig` and `.authinfo` should be edited to contain info necessary for ghub/magit/forge for communicating with github.


## Known issues

- global command log mode isn't initialized on start-up even though it's set in `init.el`
