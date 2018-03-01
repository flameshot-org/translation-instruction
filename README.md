# [Flameshot](https://flameshotapp.github.io) Translations

## How to translate

1. Download Qt Linguist using below download link.
I highly recommend  you to translate the `.ts` files using [Qt Linguist](http://doc.qt.io/qt-5/qtlinguist-index.html), though you may edit  them with a text editor.
Qt Linguist download link:
* [Windows x64](https://github.com/thurask/Qt-Linguist/releases/download/20171103/linguist.exe) 

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

## How to contribute
* Translate.
* Send a pull request.
   * If you don't know how to send a pull request, [create an issue](https://github.com/flameshotapp/translations/issues) and tell me where I can download your translation.
* Your translation will be included in the next version of Flameshot.

## Status

| Language              | Code  | Status      | Contributors |
| --------------------- | ----- | ----------- | ------------ |
| Spanish | es |  :bookmark:v0.1.0    | [lupoDharkael](https://github.com/lupoDharkael) |
| Catalan | ca |  :bookmark:v0.5.0    | [joamuran](https://github.com/joamuran) |
| Russian | ru |  :bookmark:v0.5.1   | [Shatur95](https://github.com/Shatur95) |
| Chinese (Simplified)  | zh_CN | :bookmark:v0.5.1 | [copie](https://github.com/copie), [hosiet](https://github.com/hosiet) |
| Chinese (Traditional) | zh_TW | :bookmark:v0.5.1 | [PeterDaveHello](https://github.com/PeterDaveHello) |
| Turkish               | tr | :bookmark:v0.5.1 | [oltulu](https://github.com/oltulu) |
| Georgian              | ge | :bookmark:v0.5.1 | [giogziro95](https://github.com/giogziro95) |
| French                | fr | :bookmark:v0.5.1 | [ld892012](https://github.com/ld892012) |
| Polish                | pol | :bookmark:v0.5.1 | [napcok](https://github.com/napcok) |
