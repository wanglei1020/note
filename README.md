# 日常笔记

## docker

> - <http://www.ruanyifeng.com/blog/2018/02/docker-tutorial.html>
> - <https://www.ruanyifeng.com/blog/2018/02/docker-wordpress-tutorial.html>
> - <https://juejin.cn/post/6932808129189150734>

### 关联目录

```bash
docker container run name -v ${pwd}:/app
```

## 前端工具

- [大前端工具百宝箱](https://github.com/fyuanfen/note/blob/master/tools/fe_tools.md)

### css

- [hint.css](https://github.com/chinchang/hint.css) 一款非常小巧的提示框效果
- [hover.css](http://ianlunn.github.io/Hover/) 很多鼠标 Hover 态的效果
- [head](https://github.com/joshbuchea/HEAD) 网页 `head` 元素整理

### js

- [push.js](https://pushjs.org/)基于 `Notification` API 实现的桌面效果的提示栏。浏览器支持情况不错
- [nprogress.js](https://github.com/rstacruz/nprogress/) 使页面加载时有更好的loading效果
- [notie.js](https://github.com/jaredreich/notie) 一个简单的通知库
- [Fabric.js](https://github.com/fabricjs/fabric.js) 是一个功能强大且操作简单的 Javascript HTML5 canvas
  工具库（[教程](https://juejin.cn/post/7026941253845516324)）
- [vue-cropper](https://github.com/xyxiao001/vue-cropper) 一个优雅的图片裁剪插件
- [postcss-px-to-viewport](https://github.com/evrone/postcss-px-to-viewport) 将px单位转换为视口单位的 (vw, vh, vmin,
  vmax) 的 PostCSS 插件
    - [自适应布局方案](https://juejin.cn/post/6867874227832225805)

### three.js

- [Three.js Editor Extension](https://chrome.google.com/webstore/detail/threejs-editor-extension/fbgbekpggeldiacgjkacbkkcbjhmakea?utm_source=chrome-ntp-icon)
  three.js 浏览器调试工具

### chrome插件

- [Wappalyzer](https://www.wappalyzer.com/) 网站技术栈分析
- [SingleFile](https://github.com/gildas-lormeau/SingleFile) 将网页保存为单文件
- [DarkReader](https://github.com/darkreader/darkreader) 为网站生成黑暗模式

## TIPS

### css

- [中文内容不可换行](https://www.zhangxinxu.com/wordpress/2022/06/css-line-break-word-wrap-all/)
  > 如果希望中文内容不能成为换行点，可以使用如下所示的 CSS 声明：<br>
  `word-break:keep-all;`<br>
  此设置不会影响英文内容，也就是英文句子该换行还是换行，只中文内容变得不会自动换行。

### js

- [History.scrollRestoration](https://developer.mozilla.org/zh-CN/docs/Web/API/History/scrollRestoration)
  （如何实现页面刷新后不定位到之前的滚动位置）
- `Array.from()`可以接受一个函数作为第二个参数，作用类似于数组的`map()`方法，用来对每个元素进行处理，将处理后的值放入返回的数组。

### 命令

- 查看被占用的端口（windows） `netstat -ano | findstr 端口号`
- 查看指定 PID 的进程 `tasklist|findstr PID`

### vue3

- [`setup` 中使用 `$refs`](https://markus.oberlehner.net/blog/refs-and-the-vue-3-composition-api/)

### chrome dev tool

- `ctrl` + `shift` + `D` 切换工具停靠位置