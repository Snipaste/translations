# [Snipaste](https://snipaste.com) Translations

## How to contribute
* Translate (see below for instructions).
* Send a pull request.
   * If you don't know how to send a pull request:
     * [Create an issue](https://github.com/Snipaste/translations/issues) and tell us where we can download your translation.
     * Or, you may just email the language files to snipaste.app@gmail.com.
* Tell us your name (or id) and link as a contributor.
* Your translation will be included in the next version of Snipaste.

## How to translate

Though you may open the .ts files with a text editor,
we strongly recommend you translate them using [Qt Linguist](http://doc.qt.io/qt-5/qtlinguist-index.html).

For your convenience, we have prepared the portable packages of Qt Linguist:
* [Windows x64](https://bitbucket.org/liule/snipaste/downloads/VC2015_dll_x64.zip) | [Windows x86](https://bitbucket.org/liule/snipaste/downloads/VC2015_dll_x86.zip)

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
| Chinese (Simplified)  | zh_cn | **v1.14**   | [liulex](https://github.com/liulex) |
| Chinese (Traditional) | zh_tw | **v1.14**   | [zhtw](http://greedphantom.blogspot.tw) |
| German                | de_de | **v1.14**   | [Samuel Marcius](http://www.fontenvironment.com) |
| Greek                 | el_gr | **v1.14**   | [geogeo.gr](http://www.geogeo.gr) |
| Swedish               | sv    | **v1.14**   | [Åke Engelbrektson](https://svenskasprakfiler.se) |
| Japanese              | ja_jp | **v1.14**   | 鳳凰院カミ |
| Portuguese (Brazil)   | pt_br | **v1.14**   | Igor Rückert |
| Polish                | pl_pl | _v1.11.3_   | [Wirus deleted my username](https://github.com/Wirus-deleted-my-username) |
| Dutch                 | nl_nl | **v1.14**   | Stephan Paternotte |
| Portuguese (Portugal) | pt_pt | _v1.13.2_   | [Luis Neves](mailto:luis.a.neves@sapo.pt) |
| Vietnamese            | vi_vn | _v1.11.3_   | [evildeepblue](mailto:it4u.mm@gmail.com) |
| French                | fr_fr | **v1.14**   | rico-sos |
| Russian               | ru    | _v1.13.5_   | [vanja-san](https://github.com/vanja-san) |
| Arabic                | ar_jo | **v1.14**   | MFMDawdeh |

## Contact

If you need any help, feel free to [create an issue](https://github.com/Snipaste/translations/issues). We will help you.
