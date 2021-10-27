# Bmad Tao School

## Getting Started

Please click at "Launch Binder" to get started. [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hhslepicka/bmad-school-binder/HEAD)

## For Maintainers

### Adding new System Packages

To add new system packages to be used with this Binder modify the `.binder/apt.txt` file.

### Adding new Python Packages

To add new Python packages to be used with this Binder modify the `.binder/environment.yml`.

This is a YAML file for Conda which can also install packages from PyPI via pip.


### Defining Environment Variables

To define or modify an existing environment variable modify the `.binder/start` file.

> :warning: **If changing this file**: don't remove the last line (`exec "@"`)!

### Performing actions before starting

If you need to perform any action before the startup of the Binder session such as clone a repository or create/copy/download/move files modify the `.binder/postBuild` file.

