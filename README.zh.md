# VUE BAIDU MAPV

<p align="center">
  <img src="https://vtvvv.github.io/vue-baidu-mapv/favicon.png" width="200px">
</p>
<p align="center">基于 VUE 2.x 的百度地图可视化组件</p>

[![npm](https://img.shields.io/npm/v/vue-baidu-mapv.svg)]()
[![Travis](https://img.shields.io/travis/vtvvv/vue-baidu-mapv.svg)]()
[![Package Quality](http://npm.packagequality.com/shield/vue-baidu-mapv.svg)](http://packagequality.com/#?package=vue-baidu-mapv)
[![npm](https://img.shields.io/npm/dm/vue-baidu-mapv.svg)]()
[![license](https://img.shields.io/github/license/vtvvv/vue-baidu-mapv.svg)]()

## 语言

- [中文](https://github.com/vtvvv/vue-baidu-mapv/blob/master/README.zh.md)
- [English](https://github.com/vtvvv/vue-baidu-mapv/blob/master/README.md)

## 说明

由 [vue-baidu-map](https://github.com/vtvvv/vue-baidu-mapv/blob/master/README.zh.md)
组件改造
#### 
底层为[baidu MapVGL](https://lbsyun.baidu.com/solutions/mapvdata)、
支持[threejs](https://threejs.org/)3D图层覆盖交互

## 文档

[https://vtvvv.github.io/vue-baidu-mapv](https://vtvvv.github.io/vue-baidu-mapv)

## 开始

### 安装

```bash
npm i --save vue-baidu-mapv
```

### 初始化

```javascript
import Vue from 'vue'
import BaiduMapv from 'vue-baidu-mapv'

Vue.use(BaiduMapv, {
  // ak 是在百度地图开发者平台申请的密钥 详见 http://lbsyun.baidu.com/apiconsole/key */
  ak: 'YOUR_APP_KEY'
})
```

### 使用
```vue
<template>
  <baidu-mapv class="map">
  </baidu-mapv>
</template>

<style>
/* 地图容器必须设置宽和高属性 */
.map {
  width: 400px;
  height: 300px;
}
</style>
```

## 贡献


## 协议

[MIT 许可证](https://opensource.org/licenses/MIT)


