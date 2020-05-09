# GameLocalization
Repository with localization files for Beat Slayer game.

Want to help? Fork this repo and commit your files to it, then create a pull request and we will overlook your changes, if they are good we will accept your translations!

If you have any problems with it, contact REDIZIT or cal3432 with Discord


## How to start

So, do you want to help translate the game? Ok I'll tell you how to do it.
~~RUN UNTIL IT'S TOO LATE~~

### Step 1: Download repository (folder with files)
Click green button 'Clone or download' and after 'Download ZIP'

### Step 2: Make some changes
Files in Master folder are localization files. You should change them.
Check 'How to continue' section to get more info.

### Step 3: Send your excellent work
When you have done your translating work, then type REDIZIT or cal3432 with Discord.
You should zip folder and send it.

Homeland will not forget your merits!


## How to continue

File has cvs table structure like below.
```
Key|LangName1|LangName2
Key1|Key text 1|Key text 2
...
```

LangName is name of language written in English (Like English, Russian, French).
Key1 is InGame value, this isn't interesting to you.
Key text 1 and 2 are localized text.
**'|'** - separator.

*Example*
```
Key|English|Russian
CloseOpen|Close, open|Закрыть, открыть
FindAndKill|Find and kill him!|Найти и убить его!
```


## Errors

If you see errors instead of text, then contact with REDIZIT or cal3432.
To get more information about errors enable console in game settings.

Errors

**[ERR Lang]** - Language not found. 
Check your language on the first line.
> In console "Language not found: *Your language*"


**[ERR Tkey]** - Translation not found.
Check your translation word for key.
> In console "Translation not found:  *Key (first row)*"



### Commenting

You can comment some lines.
If line starts with **//** then game will skip it.

*Example*
```
// Main_UI -> MainScreen
//
SliceSound|Slice sound volume|Громкость разрубания
```


### Table

This file is csv table. You can use Excel for example to edit file.
Split file with **'|'** separator.


## Shortcut

There is only one shortcut you can use in text

**[N]** or **\n** (but NOT recommended) - is new line

*Example*
```
SaberDescription|A veeeery long[N]description|Ооочень большое[N]описание
```