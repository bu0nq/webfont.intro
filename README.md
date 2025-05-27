# WebFont.Intro

Package for integrating `Intro` fonts in a web environment.

![npm](https://img.shields.io/npm/v/@bu0nq/webfont.intro?style=for-the-badge)
![npm](https://img.shields.io/npm/dm/@bu0nq/webfont.intro?style=for-the-badge)
![npm](https://img.shields.io/npm/dt/@bu0nq/webfont.intro?style=for-the-badge)
___

## Installation

This package can be deployed automatically using NPM:

```
npm i @bu0nq/webfont.intro
```

## Usage (CSS)

Font files are located in the `fonts` directory. To import all fonts, you can use:

```css
body {
  font-family: 'Intro', sans-serif;
}
```

### Importing

```css
@import "~@bu0nq/webfont.intro/intro.css";
@import "~@bu0nq/webfont.intro/intro-normal.css";
```

To import specific fonts, you can use:

```css
@import "~@bu0nq/webfont.intro/css/intro-400-normal.css";
```

## Usage (LESS)

Font files are located in the `fonts` directory. To import all fonts, you can use:

```less
body {
  font-family: 'Intro', sans-serif;
}
```

### Importing

```less
@import "~@bu0nq/webfont.intro/intro";
@import "~@bu0nq/webfont.intro/intro-normal";
```

To import specific fonts, you can use:

```less
@import "~@bu0nq/webfont.intro/less/intro-400-normal";
```

## Usage (SCSS)

Font files are located in the `fonts` directory. To import all fonts, you can use:

```scss
body {
  font-family: 'Intro', sans-serif;
}
```

### Importing

```scss
@use "~@bu0nq/webfont-intro/intro";
@use "~@bu0nq/webfont-intro/intro-normal";
```

To import specific fonts, you can use:

```scss
@use "~@bu0nq/webfont.intro/scss/intro-400-normal";
```

## Licensing

It is important to always read the license for every font that you use. Most of the fonts in the collection use the `SIL
Open Font License v1.1`. Some fonts use the `Apache 2.0` license. The Ubuntu fonts use the `Ubuntu Font License v1.0`.
