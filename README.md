# PDFmake 

[![GitHub Version](https://img.shields.io/github/release/gaomingcode/pdfmake.svg)](https://github.com/gaomingcode/pdfmake)
[![Packagist Downloads](https://img.shields.io/packagist/dm/gaomingcode/pdfmake)](https://github.com/gaomingcode/pdfmake)
[![Packagist License](https://img.shields.io/packagist/l/gaomingcode/pdfmake)](https://github.com/gaomingcode/pdfmake)

## Installation

### Composer

```
composer require gaomingcode/pdfmake
```
###


PDF document generation library for server-side and client-side in pure JavaScript.

Check out [the playground](http://bpampuch.github.io/pdfmake/playground.html) and [examples](https://github.com/bpampuch/pdfmake/tree/master/examples).

#### This is unstable master branch for version 0.2.x, for stable version 0.1.x see [branch 0.1](https://github.com/bpampuch/pdfmake/tree/0.1).

### Features

* line-wrapping,
* text-alignments (left, right, centered, justified),
* numbered and bulleted lists,
* tables and columns
  * auto/fixed/star-sized widths,
  * col-spans and row-spans,
  * headers automatically repeated in case of a page-break,
* images and vector graphics,
* convenient styling and style inheritance,
* page headers and footers:
  * static or dynamic content,
  * access to current page number and page count,
* background-layer,
* page dimensions and orientations,
* margins,
* custom page breaks,
* font embedding,
* support for complex, multi-level (nested) structures,
* table of contents,
* helper methods for opening/printing/downloading the generated PDF,
* setting of PDF metadata (e.g. author, subject).

## Documentation

Documentation URL: https://pdfmake.github.io/docs/

## Building from sources

using npm:
```
git clone https://github.com/bpampuch/pdfmake.git
cd pdfmake
npm install
npm run build
```

using yarn:
```
git clone https://github.com/bpampuch/pdfmake.git
cd pdfmake
yarn
yarn run build
```

## License
MIT

## Authors
* [@bpampuch](https://github.com/bpampuch) (founder)
* [@liborm85](https://github.com/liborm85)

pdfmake is based on a truly amazing library [pdfkit](https://github.com/devongovett/pdfkit) (credits to [@devongovett](https://github.com/devongovett)).

Thanks to all contributors.
