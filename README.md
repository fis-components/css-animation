# css-animation
---

make css animation easier

[![NPM version][npm-image]][npm-url]

[npm-image]: http://img.shields.io/npm/v/css-animation.svg?style=flat-square
[npm-url]: http://npmjs.org/package/css-animation

## Development

```
npm install
npm start
```

## Example

http://localhost:9001/examples/

online example: http://yiminghe.github.io/css-animation/build/examples/


## Feature

* support ie8,ie8+,chrome,firefox,safari

## install

[![css-animation](https://nodei.co/npm/css-animation.png)](https://npmjs.org/package/css-animation)

## Usage

```js
var anim = require('css-animation');
anim(el,animationName,function(){});
```

## API

### void anim(el:DOMElement, animationName:String, callback:Function)

<table class="table table-bordered table-striped">
    <thead>
    <tr>
        <th style="width: 100px;">name</th>
        <th style="width: 50px;">type</th>
        <th style="width: 50px;">default</th>
        <th>description</th>
    </tr>
    </thead>
    <tbody>
        <tr>
          <td>el</td>
          <td>DOMElement</td>
          <td></td>
          <td>dom element to be animated</td>
        </tr>
        <tr>
          <td>animationName</td>
          <td>String</td>
          <td></td>
          <td>will add animationName as class to el,then setTimeout 0 to add ${animationName}-active to el</td>
        </tr>
        <tr>
          <td>callback</td>
          <td>Function</td>
          <td></td>
          <td>triggered when anim caused by animationName is done</td>
        </tr>
    </tbody>
</table>


## Test Case

http://localhost:9001/tests/runner.html?coverage

## Coverage

http://localhost:9001/node_modules/rc-server/node_modules/node-jscover/lib/front-end/jscoverage.html?w=http://localhost:9000/tests/runner.html?coverage

## License

css-animation is released under the MIT license.
