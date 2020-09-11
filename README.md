# [flameshot](https://flameshot-org.github.io) Translation instructions

## How to translate

1. Download Qt Linguist using below download link.
I highly recommend  you to translate the `.ts` files using [Qt Linguist](http://doc.qt.io/qt-5/qtlinguist-index.html), though you may edit  them with a text editor.
Qt Linguist download link:
* [5.15.0 for Windows](https://github.com/thurask/Qt-Linguist/releases/download/20200811/linguist_5.15.0.zip) 

2. Open file `Internationalization_es.ts` in Qt Linguist, translate all phrases in its interface.
Basic steps to translate using Qt Linguist:
<details>
<img src="https://user-images.githubusercontent.com/10769951/36840468-06f93926-1d80-11e8-8426-4f5a751ea25c.jpg" alt="linguist"/>
</details>

## How to add a new language

(Suppose your language code is `abc`.)
1. Download `Internationalization_es.ts` and rename it to `Internationalization_abc.ts`.
2. Open `Internationalization_abc.ts` with your favorite text editor, replace the 3rd line with `<TS version="2.1" language="abc">`, save and quit.
3. Then open and translate `Internationalization_abc.ts` using Qt Linguist.
***NOTE.*** Translation files begin with "Internationalization", noting that "Internationalization" is initialized with a **capital letter**.

## How to contribute
* Translate.
* Send a pull request to [repo](https://github.com/flameshot-org/flameshot).
   * If you don't know how to send a pull request, [create an issue](https://github.com/flameshot-org/translation-instruction/issues) and tell me where I can download your translation.
* Your translation will be included in the next version of flameshot.

## Status

| Language              | Language Code | Status      | Contributors |
| --------------------- | ----- | ----------- | ------------ |
| Spanish             | es |  :bookmark:v0.1.0    | [lupoDharkael](https://github.com/lupoDharkael), [AlfredoRamos](https://github.com/AlfredoRamos)(minor fix), [Kiroc](https://github.com/Kiroc)(minor fix), [aluaces](https://github.com/aluaces)(typos fix) |
| Catalan | ca    |  :bookmark:v0.5.0    | [joamuran](https://github.com/joamuran) |
| Russian | ru    |  :bookmark:v0.5.1   | [Shatur95](https://github.com/Shatur95), [alok1111](https://github.com/alok1111)(update), [greno4ka](https://github.com/greno4ka)(typos fix), [AlexP11223](https://github.com/AlexP11223) |
| Chinese (S) | zh_CN | :bookmark:v0.5.1 | [copie](https://github.com/copie), [hosiet](https://github.com/hosiet)(improve translation) |
| Chinese (T) | zh_TW | :bookmark:v0.5.1 | [PeterDaveHello](https://github.com/PeterDaveHello) |
| Turkish               | tr | :bookmark:v0.5.1 | [oltulu](https://github.com/oltulu) |
| Georgian              | ka | :bookmark:v0.5.1 | [giogziro95](https://github.com/giogziro95) |
| French                | fr | :bookmark:v0.5.1 | [ld892012](https://github.com/ld892012), [aaaaadrien](https://github.com/aaaaadrien), [damosse31](https://github.com/damosse31) |
| Polish                | pl | :bookmark:v0.5.1 | [napcok](https://github.com/napcok) |
| Hungarian             | hu | :bookmark:v0.6.0 | [fxdave](https://github.com/fxdave) |
| Japanese              | ja | :bookmark:v0.8.0 | [sicklylife-jp](https://github.com/sicklylife-jp) |
| Portuguese (Brazil) | pt_BR | :bookmark:v0.8.0 | [Streppel](https://github.com/Streppel) |
| Serbian               | sr_SP | :bookmark:v0.8.0 | [cobisimo](https://github.com/cobisimo) |
| Dutch | nl | :bookmark:v0.8.0 | [Vistaus](https://github.com/Vistaus) |
| Ukrainian | uk | :bookmark:v0.8.0 | [VBoden](https://github.com/VBoden) |
| German (Germany) | de_DE | :bookmark:v0.8.0 | [DaVukovic](https://github.com/DaVukovic) |
| Slovak | sk | :bookmark:v0.8.0 | [jose1711](https://github.com/jose1711) |
| Basque (Spain) | eu_ES | :bookmark:v0.8.0 | [alexgabi](https://github.com/alexgabi), [Porrumentzio](https://github.com/Porrumentzio) |
| Czech | cs | :bookmark:v0.8.0 | [luzpaz](https://github.com/luzpaz) |
| Swedish (Sweden) | sv_SE | :bookmark:v0.8.0 | [theschitz](https://github.com/theschitz) |
| Italian | it | :bookmark:v0.8.0 | [albanobattistella](https://github.com/albanobattistella) |
| Korean | ko | :bookmark:v0.8.0 | [sheepjin99](https://github.com/sheepjin99) |
| Dutch (Netherlands) | nl_NL | :bookmark:v0.8.0 | [pollekepol](https://github.com/pollekepol) |

## How do you find  your language code

For language code, please follow **ISO Language Code** standards. [Here](http://www.lingoes.net/en/translator/langcode.htm)'s a table you can refer to. 

But just for reference, if you want to name your translated `.ts` file, you can look up the language code for the language you're translating from [ISO Language Code Table](https://github.com/flameshot-org/translation-instruction/blob/master/ISO_Language_Code_Table.md), it's available directly.