# Changelog

## 1.6.0
- [feat] Rax demos 支持注入自定义内容 ([#157](https://github.com/ice-lab/iceworks-cli/issues/157))
- [fix] 优化 react 组件分包下 external 的规则 ([#153](https://github.com/ice-lab/iceworks-cli/issues/153))
- [fix] 修复 demo 文件中，`$` 未被转义 ([#159](https://github.com/ice-lab/iceworks-cli/pull/159))

## 1.5.0

- [feat] 支持 rax 运行时小程序预览 ([#121](https://github.com/ice-lab/iceworks-cli/issues/121))

## 1.4.0

- [feat] 支持开发时构建 Kraken 产物 ([#142](https://github.com/ice-lab/iceworks-cli/issues/142))
- [feat] 升级 makedown parser 至 2.x ([#136](https://github.com/ice-lab/iceworks-cli/issues/136))
- [fix] pkg.name alias 精确匹配 ([#145](https://github.com/ice-lab/iceworks-cli/issues/145))

## 1.3.4

- [feat] 支持 react 组件 watchDist ([#120](https://github.com/ice-lab/iceworks-cli/issues/120))
- [feat] 支持小程序跨端使用不同的后缀的类型文件
- [feat] 支持 css module
- [fix] 修复 rax 组件 demo 使用 rax-portal 报错 ([#110](https://github.com/ice-lab/iceworks-cli/issues/110))
- [fix] 修复 yaml 升级 v4 导致 api 变更 ([#116](https://github.com/ice-lab/iceworks-cli/issues/116))

## 1.3.0

- [feat] 支持小程序预览 ([#66](https://github.com/ice-lab/iceworks-cli/issues/66), [#53](https://github.com/ice-lab/iceworks-cli/issues/53))
- [feat] 修改 demo 样式
- [fix] 修复 inlineStyle 为 false 下，同步到 Fusion 物料样式失效
## 0.2.22

- [fix] fix invalid homepage

## 0.2.21

- [feat] support custom unpkgHost

## 0.2.20

- [fix] fail to create component-demos.js when no node_modules folder

## 0.2.19

- [fix] export declaration analyzation
- [fix] check style statement before import

## 0.2.18

- [fix] support modify babel options
- [fix] reorder style import statement of component
- [fix] ignore node_modules in folder src

## 0.2.17

- [feat] support demoTemplate to specify demo style
- [feat] support remove basicComponents
- [feat] support babelPlugins in basic config

## 0.2.16

- [feat] support `<DemoCode src="path/to/code.js" />` to display demo code
- [fix] error render cause by mulit version of react-router-dom
- [fix] ast parse error
- [fix] update demo style
- [refactor] migrate options to basic config

## 0.2.15

- [fix] compatible with markdown filename with dashed
- [fix] log diagnostics of ts emit result
- [feat] update demo style
- [feat] refactor dist build, support sourceMap, minify

## 0.2.14

- [fix] lock core-js version
- [feat] support option babelPlugins

## 0.2.13

- [hotfix] add css entry before js

## 0.2.12

- [fix] error when add style entry

## 0.2.11

- [fix] umd compile without style file

## 0.2.10

- [fix] add polyfill for component demo

## 0.2.9

- [fix] filter module when analyze depenencies

## 0.2.8

- [fix] add plugins for demo parse

## 0.2.7

- [feat] speed up compilation of declaration
- [fix] disable host check of devserver
- [fix] watch demo changes

## 0.2.6

- [feat] jest config for component development

## 0.2.5

- [fix] compatible with React 15.x

## 0.2.4

- [fix] regex for babel-loader

## 0.2.2

- [feat] support different demo in mode dev and build
- [feat] support cli options `--watch` and `--skip-demo`
- [feat] modify homepage after build

## 0.2.1
- [feat] support to generate DTS files for TS

## 0.2.0

- [feat] brand new demo for component development
- [feat] remove rax compile, rax component development will support in build-plugin-rax-component
- [feat] support option basicComponents for basic component dependent

## 0.1.5

- [fix] support target wechat-miniprogram

## 0.1.4

- [fix] add export type for packing library
- [fix] fix entry order

## 0.1.3

- [fix] ignore css files when analyze file dependenices

## 0.1.2

- [fix] compatible with demo and package info
- [fix] analyze dependencies by babel AST

## 0.1.1

- [fix] add webpack extension