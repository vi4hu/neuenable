# neumorphism

[![NPM version](https://img.shields.io/npm/v/neuenable?color=blue)](https://www.npmjs.com/package/neuenable)
[![Build Status](https://img.shields.io/github/workflow/status/rain-kun/neuenable/Quality%20and%20Publish/main)](https://github.com/rain-kun/neuenable/actions?workflow=Quality%20and%20Publish)
[![Issues](https://img.shields.io/github/issues/rain-kun/neuenable)](https://github.com/rain-kun/neuenable/issues)

[![Milestones](https://img.shields.io/github/milestones/progress/rain-kun/neuenable/2?style=social)](https://github.com/rain-kun/neuenable/milestone/2)
[![Active milestones](https://img.shields.io/github/milestones/open/rain-kun/neuenable?style=social)](https://github.com/rain-kun/neuenable/milestones?state=open)

**NOTE: This is Work in progress project, lots of testing and functionality is remaining, some given functionality may not work.**

Neumorphism Styling for your project.

## Table of contents
- [Quick start](#quick-start)
- [Use with Bootstrap](#use-with-bootstrap)
- [Examples and properties](#examples-and-properties)
- [Documentation](#documentation)


## Quick Start

Quickly add Neuenable to your project! Use jsDelivr, a free open source CDN.

## CSS
Copy-paste the stylesheet into your `<head>` of the html page.

```html
<link href="https://cdn.jsdelivr.net/npm/neuenable@0.5.3/dist/css/neuenable.min.css" rel="stylesheet" crossorigin="anonymous">
```

## JS
Some components require the use of Javascript to function. Place the following `<script>` near the end of your pages, right before the closing `</body>` tag, to enable them.

```js
<script src="https://cdn.jsdelivr.net/npm/neuenable@0.5.3/dist/js/neuenable.min.js" crossorigin="anonymous"></script>
```

## Use with Bootstrap
Bootstrap, the world's most popular framework for building responsive, mobile-first projects on the web.

Neuenable will override the styling of Bootstrap components and you will be able to use the wide range of Bootstrap functionality with Neumorphism styling.

## Examples and properties
### Colors
Text colors
- Available colors
  - dark
  - light
  - blue
  - green
  - red
  - yellow
  - black
  - white

- Class structure

```css
text-light
```

Background colors
- Available colors
  - dark
  - light
  - blue
  - green
  - red
  - yellow
- Class structure

```css
bg-light
```

### Buttons

```html
<button class="button button-light button-push button-outline border-4 curve-5">Click me</button>
<!-- Disabled-->
<button class="button button-light hover--up" disabled>Disabled</button>
<!-- border -->
<button class="button button-light button-outline border-4">Border</button>
```

## Documentation
The documentation is in the process of being written, it will be available soon.
