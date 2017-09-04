<!---

This README is automatically generated from the comments in these files:
paper-styles.html

Edit those files, and our readme bot will duplicate them over here!
Edit this file, and the bot will squash your changes :)

The bot does some handling of markdown. Please file a bug if it does the wrong
thing! https://github.com/PolymerLabs/tedium/issues

-->

[![Build status](https://travis-ci.org/PolymerElements/paper-styles.svg?branch=master)](https://travis-ci.org/PolymerElements/paper-styles)

_[Demo and API docs](https://elements.polymer-project.org/elements/paper-styles)_


## &lt;paper-styles-plus&gt;

[![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://help.github.com/articles/about-pull-requests/)

> This repo is up-to-date fork of [&lt;paper-styles&gt;](https://github.com/PolymerElements/paper-styles)

### Changes

- Removed font-roboto dependency
- Removed google colors
- Removed opacity variables
- Added `-moz-osx-font-smoothing: grayscale;`
- Converted font size to `rem` inspired by [Material Components for the web](https://github.com/material-components/material-components-web/blob/master/packages/mdc-typography/_variables.scss)
- [RSCSS](http://rscss.io/helpers.html) Helper styles

### How to use

Add this line to `bower.json`

```json
"paper-styles": "StartPolymer/paper-styles-plus#2.0.x"
```

and then run `bower install paper-styles`

### About

The `<paper-styles>` component provides simple ways to use Material Design CSS styles
in your application. The following imports are available:

1. [color.html](https://github.com/PolymerElements/paper-styles/blob/master/color.html):
a complete list of the colors defined in the Material Design [palette](https://www.google.com/design/spec/style/color.html)


1. [default-theme.html](https://github.com/PolymerElements/paper-styles/blob/master/default-theme.html): text,
background and accent colors that match the default Material Design theme


1. [shadow.html](https://github.com/PolymerElements/paper-styles/blob/master/shadow.html): Material Design
[elevation](https://www.google.com/design/spec/what-is-material/elevation-shadows.html) and shadow styles


1. [typography.html](https://github.com/PolymerElements/paper-styles/blob/master/typography.html):
Material Design [font](http://www.google.com/design/spec/style/typography.html#typography-styles) styles and sizes


1. [demo-pages.html](https://github.com/PolymerElements/paper-styles/blob/master/demo-pages.html): generic styles
used in the PolymerElements demo pages


We recommend importing each of these individual files, and using the style mixins
available in each ones, rather than the aggregated `paper-styles.html` as a whole.

## Changes in 2.0
- removed deprecated `/deep/` styles. Files removed: `classes/shadow-layout.html`, `demo.css`.
