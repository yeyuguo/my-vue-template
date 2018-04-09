# my-vue-timer

> A Vue.js project

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

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


## 初始化项目的架构出想
1. /common 文件都是存放 非业务化的代码
2. /common 公共模块，都以一个默认的入口文件导出该模块内的其他文件；
3. 所有不同功能，都以组件化提供，无论功能多小多简单
4. 开发过程，数据存放于 localstorage 中，开发完成后，更改为 docker mongodb 里；

