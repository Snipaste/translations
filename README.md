# [Snipaste](https://snipaste.com) Translations

## How to contribute
* Translate (see below for instructions).
* Send a pull request.
   * If you don't know how to send a pull request:
     * [Create an issue](https://github.com/Snipaste/translations/issues) and tell me where I can download your translation.
     * Or, you may just email the language files to snipaste.app@gmail.com.
* Tell me your name (or id) and link as a contributor.
* Your translation will be included in the next version of Snipaste.

## How to translate

Though you may open the .ts files with a text editor,
I strongly recommend you to translate them using [Qt Linguist](http://doc.qt.io/qt-5/qtlinguist-index.html).

For your convenience, I have prepared the portable packages of Qt Linguist:
* [Windows x64](https://bitbucket.org/liule/snipaste/downloads/linguist-x64.zip) | [Windows x86](https://bitbucket.org/liule/snipaste/downloads/linguist-x86.zip)

Basic steps to translate using Qt Linguist:

<details>
<img src="https://cloud.githubusercontent.com/assets/2010459/25688906/911ad78a-30b5-11e7-8dc2-c8bcd2955615.png" alt="linguist_basic"/>

Tip: You may open multiple .ts files of different languages (such as `zh_cn.ts` and `zh_tw.ts`) in the same window, used for reference.

</details>

#####
Note: Each language has two .ts files.
For example, for Simplified Chinese, the related files are `qt_zh_cn.ts` and `zh_cn.ts`.
* `qt_zh_cn.ts` contains strings from Qt's source code and only needs to be translated once.
* `zh_cn.ts` is from Snipaste's source code and will change with each release of Snipaste.

## How to add a new language

(Suppose your language code is `xyz`.)
1. Download `qt_new.ts` and rename it to `qt_xyz.ts`.
1. Open `qt_xyz.ts` with your favorite text editor, replace the 3rd line with `<TS version="2.1" language="xyz">`, save and quit.
1. Translate `qt_xyz.ts` using Qt Linguist.
1. Download `new.ts` and rename it to `xyz.ts`.
1. Repeat Step 2 and 3 for `xyz.ts`.
1. Done!

## Status

| Language              | Code  | Status      | Contributors |
| --------------------- | ----- | ----------- | ------------ |
| Chinese (Simplified)  | zh_cn | 📕 v2.2     | [liulex](https://github.com/liulex) |
| Chinese (Traditional) | zh_tw | 📖 v2.1.1   | [zhtw](http://greedphantom.blogspot.tw), [Brownsugar](https://brownsugar.tw) |
| German                | de_de | 📕 v2.2     | [Samuel Marcius](http://www.fontenvironment.com) |
| Greek                 | el_gr | 📖 v2.1.1   | [geogeo.gr](http://www.geogeo.gr) |
| Swedish               | sv    | 📖 v1.14    | [Åke Engelbrektson](https://svenskasprakfiler.se) |
| Japanese              | ja_jp | 📖 v2.1.1   | 鳳凰院カミ, [Sayori Studio](https://t.me/SayoriStudio) |
| Portuguese (Brazil)   | pt_br | 📕 v2.2     | Igor Rückert |
| Polish                | pl_pl | 📖 v1.11.3  | [Wirus deleted my username](https://github.com/Wirus-deleted-my-username) |
| Dutch                 | nl_nl | 📖 v2.1.1   | Stephan Paternotte |
| Portuguese (Portugal) | pt_pt | 📕 v2.2     | [Luis Neves](mailto:luis.a.neves@sapo.pt) |
| Vietnamese            | vi_vn | 📖 v1.11.3  | [evildeepblue](mailto:it4u.mm@gmail.com) |
| French                | fr_fr | 📕 v2.2     | rico-sos |
| Russian               | ru    | 📖 v1.14    | [vanja-san](https://github.com/vanja-san) |
| Arabic                | ar_jo | 📕 v2.2     | [MFM Dawdeh](mailto:lalalogitech@hotmail.com) |
| Turkish               | tr_tr | 📖 v2.1.1   | [mthryilmaz](https://github.com/mthryilmaz) |
| Serbian               | sr    | 📕 v2.2     | [ozzii.translate](mailto:ozzii.translate@gmail.com) |
| Spanish (Mexico)      | es_mx | 📖 v2.0.1   | [enriquedfa](https://github.com/enriquedfa) |

## Contact

If you need any help, feel free to [create an issue](https://github.com/Snipaste/translations/issues). I will help you.
