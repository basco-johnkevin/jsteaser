# jsteaser

Creates a summary for articles

[![Build Status](https://travis-ci.org/n3m6/jsteaser.png)](https://travis-ci.org/n3m6/jsteaser)

## About

A port of the PyTeaser project (https://github.com/xiaoxu193/PyTeaser) to Javascript.
PyTeaser was a port of the TextTeaser project (https://github.com/MojoJolo/textteaser) to Python from Scala.

## Installation

`npm install jsteaser`

## Example

```javascript
var JsTeaser = require('jsteaser');

var article = {
  title: 'This is the article title',
  text:  'This is the article body.'

var jsteaser = new JsTeaser(article);
var summary  = jsteaser.summarize();

console.log(summary);

```

## API

Constructor JsTeaser() takes an article object with two fields - title and text.
Call method summarize() to get the summarization

## Limitations

Needs to be further tweaked to get better results.

## License

(The MIT License)

Copyright (c) 2013 Abdulla Faraz <abdulla.faraz@gmail.com>
---
Test Case, Stop Words and Regular Expressions from the PyTeaser Project

(The MIT License)

Copyright (c) 2013 Xiao Xu

Refer to included License file

