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

## TIPS

### css

- [中文内容不可换行](https://www.zhangxinxu.com/wordpress/2022/06/css-line-break-word-wrap-all/)
    > 如果希望中文内容不能成为换行点，可以使用如下所示的 CSS 声明：<br>
      `word-break:keep-all;`<br>
      此设置不会影响英文内容，也就是英文句子该换行还是换行，只中文内容变得不会自动换行。

### js

- [History.scrollRestoration](https://developer.mozilla.org/zh-CN/docs/Web/API/History/scrollRestoration) （如何实现页面刷新后不定位到之前的滚动位置）


### 命令

- 查看被占用的端口（windows） `netstat -ano | findstr 端口号`
- 查看指定 PID 的进程 `tasklist|findstr PID`

