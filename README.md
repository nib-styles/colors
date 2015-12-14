# @nib-styles/colors

A handful of pure colour variables for the most used colours at nib. See the [nib-pattern-library](https://nib-pattern-library.firebaseapp.com/pages/colours.html) for colours.

All colours are prefixed with `color-` to prevent potential name conflicts, and for easier editor auto completion.

## Installation

    npm i --save @nib-styles/colors

## Usage

    @import "@nib-styles/colors";
    
    .box {
      background-color: $color-sneezy;
      color: $color-prince-charles;
    }

### NB:

This repo is not for defining application-specific variables (i.e. `$border-color: $color-bashful;`)


## Changelog

- 1.0.0 Breaking change, fresh start with our current colours