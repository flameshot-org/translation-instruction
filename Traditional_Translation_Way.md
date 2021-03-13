
## How to translate

1. Download Qt Linguist using below download link.
   I highly recommend  you to translate the `.ts` files using [Qt Linguist](http://doc.qt.io/qt-5/qtlinguist-index.html), though you may edit  them with a text editor.
   Qt Linguist download link:

* [5.15.2 for Windows](https://github.com/thurask/Qt-Linguist/releases/download/20201205/linguist_5.15.2.zip) 

2. Open file `Internationalization_es.ts` in Qt Linguist, translate all phrases in its interface.
   Basic steps to translate using Qt Linguist:

<details>
<img src="https://user-images.githubusercontent.com/10769951/36840468-06f93926-1d80-11e8-8426-4f5a751ea25c.jpg" alt="linguist"/>
</details>


## How to regenerate the `.ts` file

Before translating, you should regenerate the `.ts` file to get correct source code positions and new strings.

You can do this using `lupdate`, which can be found in the Qt dir, for example `~/Qt/5.12.4/gcc_64/bin/lupdate`.

Run it like this from the Flameshot repo root:

```sh
lupdate src/ -ts data/translations/Internationalization_ru.ts
```

If you are a developer building Flameshot via CMake, you can use `-DGENERATE_TS` option.

If you don't have `lupdate`/Qt installed, you can ask someone to regenarate it for you (e.g. in [Slack](https://flameshotworkspace.slack.com)).

## How to add a new language

(Suppose your language code is `abc`.)

1. Download `Internationalization_es.ts` and rename it to `Internationalization_abc.ts`.
2. Open `Internationalization_abc.ts` with your favorite text editor, replace the 3rd line with `<TS version="2.1" language="abc">`, save and quit.
3. Then open and translate `Internationalization_abc.ts` using Qt Linguist.
   ***NOTE.*** Translation files begin with "Internationalization", noting that "Internationalization" is initialized with a **capital letter**.

## How to change app language

By default Flameshot chooses the translation language based on the OS settings.
Currently there is no option in config to override this.

On Linux you can set the `LANGUAGE` environment variable.
For example, by launching via terminal: `LANGUAGE=ru_RU:ru flameshot`.
Or if you are a developer and building/running Flameshot via Qt Creator, you can do this via [project settings](img/qt-creator-env-vars.png).

## How to contribute

* Translate.
* Send a pull request to [repo](https://github.com/flameshot-org/flameshot).
  * If you don't know how to send a pull request, [create an issue](https://github.com/flameshot-org/translation-instruction/issues) and tell me where I can download your translation.
* Your translation will be included in the next version of flameshot.


## How do you find  your language code

For language code, please follow **ISO Language Code** standards. [Here](http://www.lingoes.net/en/translator/langcode.htm)'s a table you can refer to. 

But just for reference, if you want to name your translated `.ts` file, you can look up the language code for the language you're translating from [ISO Language Code Table](https://github.com/flameshot-org/translation-instruction/blob/master/ISO_Language_Code_Table.md), it's available directly.