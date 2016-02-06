# st3
My Sublime Text 3 settings.

## Installation

Go to Preferences > Browse Packages and delete/backup the _User_ folder then clone the repository: `git clone git@github.com:cretueusebiu/st3.git User`.

## Configuration

### ESLint
`npm install -g eslint`

## Terminal

Go to Preferences > Package Settings > Terminal > Settings - User and set your terminal path. On Windows I use [Git Bash](https://git-scm.com/downloads).

### Xdebug
Install [Chrome Xdebug helper](https://chrome.google.com/webstore/detail/xdebug-helper/eadndfjplgieldjbigjakmdgkmoaaaoc?hl=en), then go to Settings > Extensions > Xdebug > Options and set _IDE key_ to `Other` : `sublime.xdebug`)

Edit _php.ini_ and [configure](https://gist.github.com/cretueusebiu/0d3508922d9c618273f6) Xdebug.
