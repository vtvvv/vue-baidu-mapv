# VUE BAIDU MAPV

<p align="center">
  <img src="https://vtvvv.github.io/vue-baidu-mapv/favicon.png" width="200px">
</p>
<p align="center">Baidu MapV components for Vue 2.x</p>

[![npm](https://img.shields.io/npm/v/vue-baidu-mapv.svg)]()
[![Travis](https://img.shields.io/travis/Dafrok/vue-baidu-mapv.svg)]()
[![Package Quality](http://npm.packagequality.com/shield/vue-baidu-mapv.svg)](http://packagequality.com/#?package=vue-baidu-map)
[![npm](https://img.shields.io/npm/dm/vue-baidu-mapv.svg)]()
[![license](https://img.shields.io/github/license/dafrok/vue-baidu-mapv.svg)]()

## Languages

- [中文](https://github.com/vtvvv/vue-baidu-mapv/blob/master/README.zh.md)
- [English](https://github.com/vtvvv/vue-baidu-mapv/blob/master/README.md)

## Documentation

[https://vtvvv.github.io/vue-baidu-mapv](https://vtvvv.github.io/vue-baidu-mapv)

## Get Start

### Installation

```bash
npm i --save vue-baidu-mapv
```

### Initialization

```javascript
import Vue from 'vue'
import BaiduMapv from 'vue-baidu-mapv'

Vue.use(BaiduMapV, {
  /* Visit http://lbsyun.baidu.com/apiconsole/key for details about app key. */
  ak: 'YOUR_APP_KEY'
})
```

### Usage

```vue
<template>
  <baidu-mapv class="map">
  </baidu-mapv>
</template>

<style>
/* The container of BaiduMap must be set width & height. */
.map {
  width: 100%;
  height: 300px;
}
</style>
```

## Contributing


## License

[MIT License](https://opensource.org/licenses/MIT)