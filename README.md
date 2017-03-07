# @nib-styles/colors

A handful of colour variables for the most commonly used colours at nib.

> Colours are prefixed with `$color-` to prevent potential name conflicts, and for easier editor auto completion.

> This repo is not for defining application-specific variables (e.g. `$border-color: $color-bashful;`)

## Installation

    npm i --save @nib-styles/colors

## Usage

```js
import colors from '@nib-styles/colors';

const GreenBox = styled.div`
  background-color: ${colors.elizabeth};
  color: ${colors.white};
`;
```

```scss
@import "@nib-styles/colors";

.box {
  color: $color-charles;
  background-color: $color-sneezy;
}
```

## Change log

### 2.0.0
- break: `styled-components` js file
- Warning: We are deprecating two-word color names. `queen-elizabeth`, `prince-charles`, `prince-harry` and `princess-kate` are being stripped of their royal titles. Use `elizabeth`, `charles`, `harry` and `kate`.

### 1.0.0
- break: fresh start from our legacy colours
