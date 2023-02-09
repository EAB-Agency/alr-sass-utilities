# sass-utilities

- [Documentation](https://eabagency.github.io/alr-sass-utilities/) (via [SassDoc](http://sassdoc.com/))

## Installation

**NPM**

```shell
npm install alr-sass-utilities
```

```scss
// All utilities
@use "alr-sass-utilities";

// All functions
@use "alr-sass-utilities/functions";

// All mixins
@use "alr-sass-utilities/mixins";

// Single function
@use "alr-sass-utilities/functions/_file-name";

// Single mixin
@use "alr-sass-utilities/mixins/_file-name";
```

**Git**

```shell
git clone https://github.com/EABAgency/alr-sass-utilities.git
```

## Usage

```scss
// All utilities (installed via npm)
@use "alr-sass-utilities" as su;

div {
    @include su.button-color(green, black, yellow, black);
}
```
