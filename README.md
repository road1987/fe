我的职业是前端工程师
===

2017 年 1 月份，看完村上春树的新书《我的职业是一个小说家》，我便萌发了写一个《我的职业是前端工程师》系列文章的想法——以个人视角来看前端领域的各种技术。整个系列的文章大概有 15 篇左右，从我是如何成为一个前端工程师，到各种前端框架的知识。

关注我的微信公众号（扫描下面的二维码或搜索 Phodal）.

![QRCode](http://articles.phodal.com/qrcode.jpg)

目录
---

*   [序:为什么前端没有前途？](#序为什么前端没有前途)
*   [我要成为一个前端设计师](#我要成为一个前端设计师)
    *   [漂亮的前台](#漂亮的前台)
    *   [我要成为一个前端设计师](#我要成为一个前端设计师-1)
    *   [关于《我的职业是前端工程师》](#关于我的职业是前端工程师)
*   [入门不是应该很简单吗？](#入门不是应该很简单吗)
    *   [前端之路](#前端之路)
    *   [我的前端入门](#我的前端入门)
        *   [我的第一个网站](#我的第一个网站)
        *   [Copy/Paste from Cookbook](#copypaste-from-cookbook)
        *   [开发工具](#开发工具)
        *   [jQuery 是最好用的](#jquery-是最好用的)
*   [学习前端只需要三个月【语言篇】](#学习前端只需要三个月语言篇)
    *   [JavaScript 语言的变化](#javascript-语言的变化)
        *   [JavaScript](#javascript)
        *   [ES6+](#es6)
        *   [TypeScript](#typescript)
    *   [小结](#小结)
*   [如何选择合适的前端框架，告别选择恐惧症](#如何选择合适的前端框架告别选择恐惧症)
    *   [前端的选择恐惧症](#前端的选择恐惧症)
        *   [技术选型：不仅仅受技术影响](#技术选型不仅仅受技术影响)
        *   [上线时间影响框架](#上线时间影响框架)
        *   [锤子定律：你需要更大的视野](#锤子定律你需要更大的视野)
    *   [前端框架一览](#前端框架一览)
        *   [jQuery, 使用生态解决问题](#jquery-使用生态解决问题)
        *   [Backbone.js，脊椎连接框架](#backbone.js脊椎连接框架)
        *   [Angular，一站式提高生产力](#angular一站式提高生产力)
        *   [React，组件化提高复用](#react组件化提高复用)
        *   [Vue.js，简单也是提高效率](#vue.js简单也是提高效率)
        *   [小结](#小结-1)
    *   [总结](#总结)
*   [前端工程师必会的六个调试技能](#前端工程师必会的六个调试技能)
    *   [我的调试入门](#我的调试入门)
    *   [基本调试技巧：实时调试](#基本调试技巧实时调试)
        *   [实时调试样式](#实时调试样式)
        *   [实时调试代码](#实时调试代码)
    *   [移动设备调试](#移动设备调试)
        *   [模拟真机：设备模拟器](#模拟真机设备模拟器)
        *   [真机调试：Device Inspect](#真机调试device-inspect)
    *   [网络调试](#网络调试)
        *   [网络调试](#网络调试-1)
        *   [使用插件](#使用插件)
    *   [小结](#小结-2)
*   [如何以正确的姿势练习，深化前端知识](#如何以正确的姿势练习深化前端知识)
    *   [前端项目的练习过程](#前端项目的练习过程)
        *   [Output is Input](#output-is-input)
        *   [练习框架、技术的时机](#练习框架技术的时机)
    *   [练习的过程](#练习的过程)
    *   [练习框架、技术的技巧](#练习框架技术的技巧)
        *   [使用模板](#使用模板)
        *   [做点什么应用](#做点什么应用)
        *   [编写一个博客应用](#编写一个博客应用)
        *   [输入和总结](#输入和总结)
    *   [其它](#其它)
        *   [关于练手项目](#关于练手项目)
*   [前后端分离，你应该知道的八件事](#前后端分离你应该知道的八件事)
    *   [前后端分离](#前后端分离)
        *   [什么是前后端分离？](#什么是前后端分离)
        *   [真的需要前后端分离吗？](#真的需要前后端分离吗)
        *   [前后端分离将遇到的那些挑战](#前后端分离将遇到的那些挑战)
    *   [前后端分离的核心：后台提供数据，前端负责显示](#前后端分离的核心后台提供数据前端负责显示)
        *   [输出逻辑：数据显示](#输出逻辑数据显示)
        *   [不可避免的前端逻辑：表单](#不可避免的前端逻辑表单)
*   [SEO 优化技巧 ：如何设计一个高质量的 URL 及页面标题](#seo-优化技巧-如何设计一个高质量的-url-及页面标题)
    *   [搜索引擎优化都是前端的活](#搜索引擎优化都是前端的活)
    *   [如何设计一个高质量的 URL](#如何设计一个高质量的-url)
        *   [受 RESTful API 影响 的 URL 设计](#受-restful-api-影响-的-url-设计)
        *   [手动自定义 URL](#手动自定义-url)
        *   [详情页 ：简单的 URL 生成规则](#详情页-简单的-url-生成规则)
        *   [自动化 URL：分类与多级目录](#自动化-url分类与多级目录)
        *   [搜索结果页：将参数融入 URL](#搜索结果页将参数融入-url)
    *   [自动生成高质量的站点标题](#自动生成高质量的站点标题)
        *   [什么是站点标题？](#什么是站点标题)
        *   [什么才算一个高质量的站点标题？](#什么才算一个高质量的站点标题)
*   [你应该知道的单页面应用的五要素](#你应该知道的单页面应用的五要素)
    *   [单页面应用的演进](#单页面应用的演进)
    *   [路由：页面跳转与模块关系](#路由页面跳转与模块关系)
    *   [数据：获取与鉴权](#数据获取与鉴权)
    *   [数据展示：模板引擎](#数据展示模板引擎)
    *   [交互：事件与状态管理](#交互事件与状态管理)
        *   [组件交互：状态管理](#组件交互状态管理)
        *   [用户交互：事件](#用户交互事件)
*   [数据存储](#数据存储)
    *   [LocalStorage](#localstorage)
    *   [WebSQL](#websql)
    *   [IndexedDB](#indexeddb)
    *   [SQLite](#sqlite)
*   [前端也需要性能优化](#前端也需要性能优化)
    *   [Timeline](#timeline)
    *   [首屏加载优化](#首屏加载优化)
    *   [缓存优化](#缓存优化)
    *   [生命周期优化](#生命周期优化)
    *   [HTML5 图片缓存](#html5-图片缓存)
    *   [资源缓存， API 结果](#资源缓存-api-结果)
*   [前端移动开发](#前端移动开发)
    *   [移动开发的三种类型](#移动开发的三种类型)
        *   [Web 应用](#web-应用)
        *   [混合应用](#混合应用)
        *   [React Native](#react-native)
    *   [响应式设计](#响应式设计)
    *   [用户体验](#用户体验)
    *   [性能](#性能)
*   [API 使用 与 设计 ？](#api-使用-与-设计)
*   [前端工程化思维](#前端工程化思维)
    *   [自动化构建](#自动化构建)
    *   [集成测试](#集成测试)
*   [如何以正确的姿势从零开发一个前端应用](#如何以正确的姿势从零开发一个前端应用)
    *   [了解真实世界的需求](#了解真实世界的需求)
    *   [确认技术方案](#确认技术方案)
    *   [选择技术栈](#选择技术栈)
    *   [搭建构建系统](#搭建构建系统)
    *   [定义前端接口 - 使用 Mock Server](#定义前端接口---使用-mock-server)
    *   [实现后台接口](#实现后台接口)
    *   [对接应用，编写测试](#对接应用编写测试)
    *   [上线](#上线)


前端技能
---

来源：[https://github.com/phodal/awesome-growth](https://github.com/phodal/awesome-growth)

 - 基础
   * HTML / CSS
   * JavaScript
   * DOM
 - 中级篇 
   * 数据格式（如JSON、XML）
   * RESTful API交互（如jQuery Ajax，Fetch API，ReactiveX）
   * 正则表达式
   * HTML语义化
   * 命令行
   * Node.js
   * DIV / CSS
   * SCSS / SASS 
   * 矢量图形 / 矢量图形动画（如SVG）
   * 单页面应用
 - 高级篇
   * ES6 / TypeScript 
   * CSS3
   * 面向对象编程
   * 函数式编程
   * MVC / MVVM / MV*
   * 安全性（如跨域）
   * 授权（如HTTP Basic、JWT等等）
 - 工程化
   * 代码质量（如JSLint / ESLint / TSLint / CSLint）
   * 代码分析（如Code Climate）
   * 测试覆盖率
   * 构建系统（gulp、grunt、webpack等等）
   * 自动构建（脚本）
 - 兼容性
   *  跨浏览器测试 （Chrome，IE，Firefox，Safari等等）
   *  跨平台测试（Windows、GNU/Linux，Mac OS等等）
   *  跨设备测试（Desktop，Android，iOS，Windows Phone）
   *  跨版本测试（同一个浏览器的不同版本）
 - 前端特定
   * CSS / CSS3 动画
   * JavaScript 动画
   * Web字体嵌入
   * Icon 字体
   * 图形和图表
   *  CSS Sprite（如glue）
   * DOM操作（如jQuery、React等等）
   * 模板引擎（如JSX、Handlebars、JSP、Mustache等等）
 - 软件工程
   * 版本管理（如git、svn） 
   * 包管理（如npm、bower）
   * 依赖管理
   * 模块化（如CommonJS、WebPack）
 - 调试
   * 浏览器调试
   * Debug工具
   * Wireshark / Charles抓包
   * 远程设备调试（如Chrome Inspect Devices）
 - 测试
   * 单元测试
   * 服务测试
   * UI测试
   * 集成测试
 - 性能与优化
   * PageSpeed / Yslow 优化
   * 加载优化（如gzip压缩、缓存等等）
   * 性能测试（特别是移动Web）
   * 可用性
   * 压缩（如Minify、Uglify、CleanCSS等等）
 - 设计
   * 切页面
   * 线框图（Wireframe）
   * 响应式设计
   * 网格布局（Grid Layout）
   * Flexbox布局
 - SEO
   * Sitemap（站点地图）
   * 内部链接建设
   * MicroData / MicroFormat
   * 页面静态内容生成
   * H1、H2、H3和strong使用
   * Title、Description优化
   * 页面静态内容生成

LICENSE
---

[![Phodal's Article](http://brand.phodal.com/shields/article-small.svg)](https://www.phodal.com/) [![Phodal's Book](http://brand.phodal.com/shields/book-small.svg)](https://www.phodal.com/)


© 2017 [Phodal Huang](https://www.phodal.com). This code is distributed under the Creative Commons Attribution-Noncommercial-No Derivative Works 3.0  License. See `LICENSE` in this directory.

[待我代码编成，娶你为妻可好](http://www.xuntayizhan.com/blog/ji-ke-ai-qing-zhi-er-shi-dai-wo-dai-ma-bian-cheng-qu-ni-wei-qi-ke-hao-wan/)
