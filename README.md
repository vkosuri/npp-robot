# lang-robot

Robotframework syntax highlighting for **GEdit** and **Notepad++**

# Table of Contents
1. [GEdit](#gedit)
2. [Notepad++](#notepad)

## Gedit

``` Shell
sudo cp ./robot.lang  /usr/share/gtksourceview-3.0/language-specs/robot.lang
```

![copy-robot](https://cloud.githubusercontent.com/assets/13664257/12109003/9dfd7f2e-b3a3-11e5-8896-b283186c8242.png)

chmod the file  /usr/share/gtksourceview-3.0/language-specs/robot.lang

``` Shell
sudo chmod 644 /usr/share/gtksourceview-3.0/language-specs/robot.lang
```

![disp-robot](https://cloud.githubusercontent.com/assets/13664257/12109041/108b99e0-b3a4-11e5-8770-2e0c1d8235e0.png)

## Notepad++
## Importing a user defind language

Langugage -> User-Defined

![alt text](http://docs.notepad-plus-plus.org/images/1/1a/Udl_tuto02.gif "User-Defined")

Select Import

![alt text](http://docs.notepad-plus-plus.org/images/8/80/Ulds_undock.png "Import")

Select UDL xml **lang-robot.xml** file

Below screen shot summaries the how it looks and color represents

```
Blue - Keywords
Orange - Variables
Green - Comments
```

![syntax-highlighter](https://cloud.githubusercontent.com/assets/13664257/12018694/650545a2-ad8c-11e5-8bf2-52719ab60f0a.png)


Enjoy...
