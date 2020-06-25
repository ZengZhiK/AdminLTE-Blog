<h1 align="center"><a href="https://github.com/ZengZhiK/AdminLTE-Blog" target="_blank">AdminLTE-Blog</a></h1>
> AdminLTE based personal blog HTML page template | 基于AdminLTE搭建的个人博客前端页面模板，包括前台页面和后台页面，集成markdown编辑器、博客目录生成等插件，可以结合后端制作个人博客系统！

------

## 简介

一直想写一个个人博客系统，但找不到合适的前端模板页面，在github上偶然发现[AdminLTE](https://github.com/ColorlibHQ/AdminLTE)，这是一套后台管理模板页面，基于Bootstrap开发，提供了很多css样式，并可以集成不同的jquery插件，个人觉得写得非常nice，故在此基础上开发了一套个人博客页面模板。本项目基本功能已经完成，细节方面：例如表单校验、表单提交（尤其是异步提交）还需完善，下面为页面展示及其使用插件介绍。

## 前台页面

1.首页 **index.html**

<img src="https://cdn.jsdelivr.net/gh/ZengZhiK/PicBed/AdminLTE-Blog开源项目/index.png"/>

2.分类页 **category.html**

<img src="https://cdn.jsdelivr.net/gh/ZengZhiK/PicBed/AdminLTE-Blog开源项目/category.png"/>

3.标签页 **tag.html**

<img src="https://cdn.jsdelivr.net/gh/ZengZhiK/PicBed/AdminLTE-Blog开源项目/tag.png"/>

4.归档页 **archive.html**

<img src="https://cdn.jsdelivr.net/gh/ZengZhiK/PicBed/AdminLTE-Blog开源项目/archive.png"/>

5.留言页 **guestbook.html**

<img src="https://cdn.jsdelivr.net/gh/ZengZhiK/PicBed/AdminLTE-Blog开源项目/guestbook.png"/>6.详情页 **detail.html**

**使用插件：**

`tocbot`[https://github.com/tscanlin/tocbot](https://github.com/tscanlin/tocbot)：用于生成右侧目录

`prism`[https://github.com/PrismJS/prism](https://github.com/PrismJS/prism)：语法高亮

<img src="https://cdn.jsdelivr.net/gh/ZengZhiK/PicBed/AdminLTE-Blog开源项目/detail.png"/>

## 后台页面

1.登录页 **login.html**

<img src="https://cdn.jsdelivr.net/gh/ZengZhiK/PicBed/AdminLTE-Blog开源项目/login.png"/>

2.后台首页(仪表板) **dashboard.html**

<img src="https://cdn.jsdelivr.net/gh/ZengZhiK/PicBed/AdminLTE-Blog开源项目/dashboard.png"/>

3.博客编辑页 **edit.html**

**使用插件：**

`select2`[https://github.com/select2/select2](https://github.com/select2/select2)：下拉框

`editor.md`[https://github.com/pandao/editor.md](https://github.com/pandao/editor.md)：markdown编辑器

`sweetalert2`[https://github.com/sweetalert2/sweetalert2](https://github.com/sweetalert2/sweetalert2)：一个漂亮的弹出框

`selectize`[https://github.com/selectize/selectize.js](https://github.com/selectize/selectize.js)：多输入文本框

`icheck`[https://github.com/fronteed/icheck](https://github.com/fronteed/icheck)：checkbox和radio美化

<img src="https://cdn.jsdelivr.net/gh/ZengZhiK/PicBed/AdminLTE-Blog开源项目/edit.png"/>

4.博客管理页 **blog-mgr.html**

**使用插件：**

`DataTables`[https://github.com/DataTables/DataTables](https://github.com/DataTables/DataTables)：表格生成

<img src="https://cdn.jsdelivr.net/gh/ZengZhiK/PicBed/AdminLTE-Blog开源项目/blog-mgr.png"/>

5.分类管理页 **category-mgr.html**

**使用插件：**

`selectize`[https://github.com/selectize/selectize.js](https://github.com/selectize/selectize.js)：多输入文本框

<img src="https://cdn.jsdelivr.net/gh/ZengZhiK/PicBed/AdminLTE-Blog开源项目/category-mgr.png"/>

6.标签管理页 **tag-mgr.html**

**使用插件：**

`selectize`[https://github.com/selectize/selectize.js](https://github.com/selectize/selectize.js)：多输入文本框

<img src="https://cdn.jsdelivr.net/gh/ZengZhiK/PicBed/AdminLTE-Blog开源项目/tag-mgr.png"/>

7.评论管理页 **comment-mgr.html**

<img src="https://cdn.jsdelivr.net/gh/ZengZhiK/PicBed/AdminLTE-Blog开源项目/comment-mgr.png"/>

8.系统配置页 **configuration.html**

**使用插件：**

`selectize`[https://github.com/selectize/selectize.js](https://github.com/selectize/selectize.js)：多输入文本框

<img src="https://cdn.jsdelivr.net/gh/ZengZhiK/PicBed/AdminLTE-Blog开源项目/configuration.png"/>