<!--
 * @Author: liva
 * @Date: 2019-07-26 09:25:28
 * @LastEditors: liva
 * @LastEditTime: 2019-08-23 15:51:37
 -->

# 移动端 ui 样式库

## 说明

本插件依赖 font-awesome@4.7.0，安装本插件的同时也会安装 font-awesome。在使用本 UI 样式库的时候可以直接引用对应的 CSS 文件：

import 'font-awesome/css/font-awesome.min.css';
import 'ui-mobile-liva/css/ui.min.css';

同时，本插件已经使用 js 文件打包了两个 css 文件，在支持 CSS 模块的项目里也可以像下面这样直接引用插件：

import 'ui-mobile-liva';

## 变更记录

0.1.1

- 【Initial】初始版本

  0.1.2

- 【Add】Panel 组件的标题部分添加“查看更多”这种引导链接的样式。
- 【Bug Fix】Search 组件指定 z-index，解决和有定位元素同时使用时的层级错乱问题。
