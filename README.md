# sublime-text-settings
This is repository for sync my sublime text3 settings and packages.

## Setup settings
```
$ cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
$ git init
$ git add Package\ Control.sublime-settings
$ git commit -am "settings from from <device name>"
$ git remote add origin https://github.com/<github name>/<repo name>.git
$ git push -u origin master
```

## Apply the settings to other machines by using below git command:
```
$ git init
$ git remote add origin https://github.com/Suppasit/sublime-pref.git
$ git fetch
$ git reset --hard origin/master
```

## Sync across OS (Linux and Windows)
I prefer to use **_Consolas_** as my font face but it not available on Linux based OS.
So, I choosed **_Inconsolata_** on Linux.

Edit the font_face in sublime text settings as below:

**Windows**
```JSON
"font_face": "Consolas",
```

**Linux**
```JSON
"font_face": "Inconsolata",
```
