# UPC-A Barcode CSS

This repository provides a modular and customizable way to assemble UPC-A barcodes directly in the browser using only HTML and CSS.

## Examples

### Exampe 1

The following example generates a UPC-A barcode for the number `2227377712652`.

```html
<div class="barcode">
  <div class="digit digit--start-stop"></div>
  <div class="digit digit--2"></div>
  <div class="digit digit--2"></div>
  <div class="digit digit--7"></div>
  <div class="digit digit--3"></div>
  <div class="digit digit--7"></div>
  <div class="digit digit--7"></div>
  <div class="digit digit--middle"></div>
  <div class="digit digit--7"></div>
  <div class="digit digit--1"></div>
  <div class="digit digit--2"></div>
  <div class="digit digit--6"></div>
  <div class="digit digit--5"></div>
  <div class="digit digit--2"></div>
  <div class="digit digit--start-stop"></div>
</div>
```

### Exampe 2

This example uses `linear-gradient` on a single element to generate the barcode.

> While making the HTML more concise, this approach may cause problems in some browsers that makes the barcode hard to scan.

```html
<div
  class="barcode"
  data-digit-01="0"
  data-digit-02="1"
  data-digit-03="2"
  data-digit-04="3"
  data-digit-05="4"
  data-digit-06="1"
  data-digit-07="6"
  data-digit-08="7"
  data-digit-09="8"
  data-digit-10="9"
  data-digit-11="0"
  data-digit-12="1"
></div>
```