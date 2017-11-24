# sublime-text-settings
This is repository for sync my sublime text3 settings and packages.

## Apply the settings to other machines by using below git command:
```
$ git init
$ git remote add origin https://github.com/eswizardry/sublime-text-settings.git
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
