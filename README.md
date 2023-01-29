# BrowserData
A simple library to check browser feature support

## Get the library
```
var data = new BrowserData();
```

## Get the browser score
```
var htmlScore = data.score.html[0];
var cssScore = data.score.css[0];
var jsScore = data.score.js[0];
var svgScore = data.score.svg[0];
```

## Verify if browser support a feature
```
var support = data.js.webGPU;
var support = data.html.abbr;
var support = data.css.margin;
var support = data.svg.rect;
```

## "getSupport" integrated
```
var support = data.support("css","margin");
```
