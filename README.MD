# wsui-enlarge
> wsui module for enlarge clickable area.

[![version][version-image]][version-url]
[![license][license-image]][license-url]
[![size][size-image]][size-url]
[![download][download-image]][download-url]

## installation
```shell
npm i @jswork/wsui-enlarge
```

## usage
```scss
// use sass
@import '~@jswork/wsui-enlarge/dist/index.scss';
// use css
@import '~@jswork/wsui-enlarge/dist/style.css';
```

```html
<style>
  button{
    position: relative;
  }
</style>

<p><button class="wsui-enlarge" data-value="small" type="button">我是可点击区域 data-value="small"</button></p>
<p><button class="wsui-enlarge" data-value="normal" type="button">我是可点击区域 data-value="normal"</button></p>
<p><button class="wsui-enlarge" data-value="large" type="button">我是可点击区域 data-value="large"</button></p>
```

## preview
- https://afeiship.github.io/wsui-enlarge/

## license
Code released under [the MIT license](https://github.com/afeiship/wsui-enlarge/blob/master/LICENSE.txt).

[version-image]: https://img.shields.io/npm/v/@jswork/wsui-enlarge
[version-url]: https://npmjs.org/package/@jswork/wsui-enlarge

[license-image]: https://img.shields.io/npm/l/@jswork/wsui-enlarge
[license-url]: https://github.com/afeiship/wsui-enlarge/blob/master/LICENSE.txt

[size-image]: https://img.shields.io/bundlephobia/minzip/@jswork/wsui-enlarge
[size-url]: https://github.com/afeiship/wsui-enlarge/blob/master/dist/wsui-enlarge.min.js

[download-image]: https://img.shields.io/npm/dm/@jswork/wsui-enlarge
[download-url]: https://www.npmjs.com/package/@jswork/wsui-enlarge

