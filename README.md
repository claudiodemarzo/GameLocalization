# GameLocalization
Repository with localization files for Beat Slayer game.

Want to help? Fork this repo and commit your files to it, then create a pull request and we will overlook your changes, if they are good we will accept your translations!

If you have any problems with it, contact REDIZIT or cal3432 with Discord


## Localization
Repository with localization files for beat slayer game and editor

Want to help? Fork this repo and commit your files to it, then create a pull request and we will overlook your changes, if they are good we will accept your translations!

### How to fork the repo:

#### 1) Press the "fork" button.

![Step 1](https://cdn.discordapp.com/attachments/695592374021390376/708627593683009556/unknown.png)

#### 2) Done, edit the translation files to your wish!

![Step 2](https://media.discordapp.net/attachments/695592374021390376/708627700620853278/unknown.png?width=788&height=485)

Once you have edited the files, see [making a pull request](https://github.com/REDIZIT/Localization#how-to-make-a-pull-request) for more infomation

### How to edit the translation files:

File has cvs table structure like below.
```
Language|English|Russian|French
Key 1|Key 1|Ключ 1|Clé 1
...
```

Seperate the languages with `|`

*Example*
```
Key|English|Russian|French
CloseOpen|Close, open|Закрыть, открыть|French Stuff
FindAndKill|Find and kill him!|Найти и убить его!|French Stuff
```


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


### Shortcut

There is only one shortcut you can use in text

**[N]** or **\n** (but NOT recommended) - is new line

*Example*
```
SaberDescription|A veeeery long[N]description|Ооочень большое[N]описание
```

## How to make a pull request:

#### 1) Open the pull requests pane.

![1](https://media.discordapp.net/attachments/695592374021390376/708627994712866816/unknown.png?width=959&height=138)

#### 2) Press create new pull request.

![2](https://media.discordapp.net/attachments/695592374021390376/708628034957344768/unknown.png)
![2](https://cdn.discordapp.com/attachments/695592374021390376/708628126778916894/unknown.png)
![2](https://media.discordapp.net/attachments/695592374021390376/708628193770209292/unknown.png?width=782&height=485)

Now wait until it gets approved or denied.

Do not delete your fork whilst you are waiting!
