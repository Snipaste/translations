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
| Chinese (Simplified)  | zh_cn | [![](https://translations.snipaste.com/widgets/snipaste/zh_Hans/master/svg-badge.svg)](https://translations.snipaste.com/projects/snipaste/master/zh_Hans/) | [liulex](https://github.com/liulex) |
| Chinese (Traditional) | zh_tw | [![](https://translations.snipaste.com/widgets/snipaste/zh_Hant/master/svg-badge.svg)](https://translations.snipaste.com/projects/snipaste/master/zh_Hant/) | [zhtw](http://greedphantom.blogspot.tw), [Brownsugar](https://brownsugar.tw) |
| German                | de_de | [![](https://translations.snipaste.com/widgets/snipaste/de_DE/master/svg-badge.svg)](https://translations.snipaste.com/projects/snipaste/master/de_DE/) | [Samuel Marcius](http://www.fontenvironment.com) |
| Greek                 | el_gr | [![](https://translations.snipaste.com/widgets/snipaste/el_GR/master/svg-badge.svg)](https://translations.snipaste.com/projects/snipaste/master/el_GR/) | [geogeo.gr](http://www.geogeo.gr) |
| Swedish               | sv    | [![](https://translations.snipaste.com/widgets/snipaste/sv/master/svg-badge.svg)](https://translations.snipaste.com/projects/snipaste/master/sv/) | [Åke Engelbrektson](https://svenskasprakfiler.se) |
| Japanese              | ja_jp | [![](https://translations.snipaste.com/widgets/snipaste/ja_JP/master/svg-badge.svg)](https://translations.snipaste.com/projects/snipaste/master/ja_JP/) | 鳳凰院カミ, [Sayori Studio](https://t.me/SayoriStudio), [雨宮千夏](https://github.com/BakaChinatsu) |
| Portuguese (Brazil)   | pt_br | [![](https://translations.snipaste.com/widgets/snipaste/pt_BR/master/svg-badge.svg)](https://translations.snipaste.com/projects/snipaste/master/pt_BR/) | Igor Rückert |
| Polish                | pl_pl | [![](https://translations.snipaste.com/widgets/snipaste/pl_PL/master/svg-badge.svg)](https://translations.snipaste.com/projects/snipaste/master/pl_PL/) | [Wirus deleted my username](https://github.com/Wirus-deleted-my-username), [mbiesiad](https://github.com/mbiesiad) |
| Dutch                 | nl_nl | [![](https://translations.snipaste.com/widgets/snipaste/nl_NL/master/svg-badge.svg)](https://translations.snipaste.com/projects/snipaste/master/nl_NL/) | Stephan Paternotte |
| Portuguese (Portugal) | pt_pt | [![](https://translations.snipaste.com/widgets/snipaste/pt_PT/master/svg-badge.svg)](https://translations.snipaste.com/projects/snipaste/master/pt_PT/) | [Luis Neves](mailto:luis.a.neves@sapo.pt) |
| Vietnamese            | vi_vn | [![](https://translations.snipaste.com/widgets/snipaste/vi_VN/master/svg-badge.svg)](https://translations.snipaste.com/projects/snipaste/master/vi_VN/) | [evildeepblue](mailto:it4u.mm@gmail.com) |
| French                | fr_fr | [![](https://translations.snipaste.com/widgets/snipaste/fr_FR/master/svg-badge.svg)](https://translations.snipaste.com/projects/snipaste/master/fr_FR/) | rico-sos |
| Russian               | ru    | [![](https://translations.snipaste.com/widgets/snipaste/ru/master/svg-badge.svg)](https://translations.snipaste.com/projects/snipaste/master/ru/) | [vanja-san](https://github.com/vanja-san) |
| Arabic                | ar_jo | [![](https://translations.snipaste.com/widgets/snipaste/ar_JO/master/svg-badge.svg)](https://translations.snipaste.com/projects/snipaste/master/ar_JO/) | [MFM Dawdeh](mailto:lalalogitech@hotmail.com) |
| Turkish               | tr_tr | [![](https://translations.snipaste.com/widgets/snipaste/tr_TR/master/svg-badge.svg)](https://translations.snipaste.com/projects/snipaste/master/tr_TR/) | [mthryilmaz](https://github.com/mthryilmaz) |
| Serbian               | sr    | [![](https://translations.snipaste.com/widgets/snipaste/sr/master/svg-badge.svg)](https://translations.snipaste.com/projects/snipaste/master/sr/) | [ozzii.translate](mailto:ozzii.translate@gmail.com) |
| Spanish (Mexico)      | es_mx | [![](https://translations.snipaste.com/widgets/snipaste/es_MX/master/svg-badge.svg)](https://translations.snipaste.com/projects/snipaste/master/es_MX/) | [enriquedfa](https://github.com/enriquedfa) |
| Korean                | ko    | [![](https://translations.snipaste.com/widgets/snipaste/ko/master/svg-badge.svg)](https://translations.snipaste.com/projects/snipaste/master/ko/) | [박경태](https://github.com/parkkyeongtae) |
| Czech                 | cs_cz | [![](https://translations.snipaste.com/widgets/snipaste/cs_CZ/master/svg-badge.svg)](https://translations.snipaste.com/projects/snipaste/master/cs_CZ/) | Štěpán Hašler |


## Contact

If you need any help, feel free to [create an issue](https://github.com/Snipaste/translations/issues). I will help you.
