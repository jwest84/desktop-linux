This repo includes scripts and files to help setup desktop linux environment

# IDE

* Install [Intellij Idea](https://www.jetbrains.com/idea/download/#section=linux)

# Browsers

* Install [Firefox](https://www.mozilla.org/en-US/exp/firefox/new/)
* Install [Google Chrome](https://www.google.com/chrome/)

# Git

* To get this repo, git should be installed via `sudo apt-get install git`
* Run   `sudo ./prepare_git_environment.sh`
* Then get copy of this repo `git clone <insert repo ssh stuff>`


# Java / Scala Development

* Run `sudo ./java8_env_setup.sh`

# Python

* Run `sudo ./python_env_setup.sh`
* Create virtualenv via `mkvirtualenv <insert a name for env>`
* Exit virtualenv with `deactivate`
* Enter previously created virtualenv `workon <name of virtualenv>`

# Useful utilities

* Run `sudo ./install_useful_utilities.sh`
** Installs PDF viewer: evince, zip
* Install [Dropbox](https://www.dropbox.com/h)
