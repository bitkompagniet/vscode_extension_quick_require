**DEPRECATED: this project has been abandoned. Take a look at tgreen7's fork instead (tgreen7.vs-code-node-require).**

This module can import or require node modules and local files.

Use the command dialog or the shortcut `Ctrl+Shift+1`. You can also use `Ctrl+Shift+2` to import/require and insert the reference at the current cursor position.

## Features

* Require core modules, dependencies / devDependencies or local files.
* New requires will be added to the end of the require block in top of file.
* The style (import vs require) will be auto-detected one a per-file level. It will ask for the first dependency.
* Typical naming substitutions (for example, `lodash` will be named `_` and jQuery will be `$`).
* If the import already exists, it will not add a duplicate.
* Can also search files within modules in the dependencies list. Default is off, as performance and usability might take a hit from a lot of files, but it can be enabled in the configuration.

## Acknowledgements

This module is a fork from [Quick Require](https://github.com/milkmidi/vscode_extension_quick_require), which was
good, but very basic. The typical namings was taken from [NodeRequirer](https://github.com/ganemone/NodeRequirer) for
Sublime Text.

## Bitkompagniet

[Bitkompagniet ApS](http://bitkompagniet.dk/) is a Danish development company specializing in tailored web applications for customers. We use modern tools and methods to get the work done, while still keeping a focus on maintainability and extensibility.

The things we develop as open source software will stay open and free.
