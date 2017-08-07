# vue-marquee-ho

> A Vue component to marquee

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```
## 使用组件
1. 通过`npm install vue-marquee-ho -s` 安装到相应的项目下，

2. 到项目中的node_modules/目录下将可以看到："vue-marquee-ho"

3. 需要用到该组件时可以这样引入

```
import VueMarquee from 'vue-marquee-ho';
import Css from 'vue-marquee-ho/dist/vue-marquee.min.css'
export default {
  name: 'app',
  components:{
      "vue-marquee": VueMarquee
    },
}
```
看一个demo:

```
<template>
  <div id="app">
    <div class="marquee-wrap" style="width: 100px;"><vue-marquee content="33333" class="two"  :showtwo="false"></vue-marquee></div>
    <div class="marquee-wrap" style="width: 100px;"><vue-marquee content="22222" class="two"  :showtwo="false"></vue-marquee></div>
    <div class="marquee-wrap" style="width: 100px;"><vue-marquee content="1" class="two"  :showtwo="false"></vue-marquee></div>
    <router-view></router-view>
  </div>
</template>

<script>
import VueMarquee from 'vue-marquee-ho';
import Css from 'vue-marquee-ho/dist/static/css/vue-marquee.min.css'
export default {
  name: 'app',
  components:{
      "vue-marquee": VueMarquee
    },
}
</script>
```

该npm 组件是基于Vue-cli 搭建的公用组件包开发.
## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
