# @nib-styles/colors

A handful of colour variables for the most commonly used colours at nib.

> Colours are prefixed with `$color-` to prevent potential name conflicts, and for easier editor auto completion.

> This repo is not for defining application-specific variables (e.g. `$border-color: $color-bashful;`)

## Installation

    npm i --save @nib-styles/colors

## Usage

```scss
@import "@nib-styles/colors";

.box {
  color: $color-prince-charles;
  background-color: $color-sneezy;
}
```

## Change log

### 1.0.0
- break: fresh start from our legacy colours
