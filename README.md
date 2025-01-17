# BLOG

[![vue](https://img.shields.io/badge/MADE%20WITH-VUE3.2-42a97a?style=for-the-badge&labelColor=35495d)](https://vuejs.org)
&nbsp;
[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/shaobeichen/blog/deploy?label=deploy&style=for-the-badge)](https://github.com/shaobeichen/blog/actions/workflows/action.yml)
&nbsp;
[![coverage](https://img.shields.io/codecov/c/github/shaobeichen/blog/master.svg?label=coverage&style=for-the-badge)](https://codecov.io/gh/shaobeichen/blog)
&nbsp;
[![GitHub stars](https://img.shields.io/github/stars/shaobeichen/blog.svg?style=for-the-badge)](https://github.com/shaobeichen/blog/stargazers)
&nbsp;

## 介绍

个人主页，Vue3.2 + Vite + TypeScript + Pinia + Setup 写法

## 特性

- 有专门用来练习 Vue3.2 的 TodoList 案例
- 可以快速入门 Vue3.2 + Vite2 + TypeScript
- 有 Vue3 + Setup 组件写法
- 有 Vue3.2 命令式组件写法，组件同时支持 Vue2.x Options API 调用
- 有 jest + TypeScript 入门写法，写出第一个 Vue 组件测试用例，查看覆盖率
- 支持 eslint、prettier、stylelint、commitlint、husky 等规范
- 支持 GitHub Actions 自动部署项目

## 用法

1.安装 yarn，如果已经安装 yarn，此步骤跳过

```
npm i -g yarn
```

2.安装依赖

```
yarn
```

3.运行项目

```
yarn dev
```

## 产出文章

> 做项目后产出了几篇文章，用于记录，帮助大家踩坑。

- [Vue3+Vite+Scss 项目踩坑记录(一)](https://juejin.cn/post/7115375597370474533)
- [Vue3+Vite+Scss 项目踩坑记录(二)](https://juejin.cn/post/7116310360986304525)
- [Vue3+Vite+Scss 项目踩坑记录(三)](https://juejin.cn/post/7117296242660474893)
- [Vue3+Vite+Scss 项目踩坑记录(四)](https://juejin.cn/post/7118400090296827911)

## 参考链接

Vue3

- [vue-vben-admin](https://github.com/vbenjs/vue-vben-admin)
- [element-plus](https://github.com/element-plus/element-plus/tree/dev/packages/components)
- [vant](https://github.com/youzan/vant)
- [vue3-music](https://github.com/SmallRuralDog/vue3-music/blob/master/src/views/playlist/PlayList.vue)
- [vue3.2-vite-template](https://github.com/BoyYangzai/vue3.2-vite-template/blob/main/src/components/Message/Message.ts)
- [Vue3 组件如何支持 Options API](https://github.com/vueComponent/ant-design-vue/issues/2810)
- [从零搭建后台系统（Vue3.0+ElementPlus+TS+Vite）(一）](https://juejin.cn/post/7038485798143918116)

jest

- [jest 中文网](https://jestjs.io/zh-Hans/docs/getting-started)
- [Vue Test Utils 2](https://test-utils.vuejs.org/guide/): 用于 Vue3 组件单元测试
- [如何运行 Jest 单元测试](https://developer.aliyun.com/article/975177)
- [vant toast test](https://github.com/youzan/vant/blob/dev/packages/vant/src/toast/test/index.spec.ts)
