---
title: 更新日志
---

## v1.2.4-v1.2.5, 2018-07-14

- `A` 新增`代码高亮` by [hanabi](https://github.com/egoist/hanabi)
- `U` 优化防`XSS` 逻辑
- `F` 修复`自定义路径`在查询时被替换的 Bug
- `F` 修复`avatar: ''`被替换成`avatar:'mm'`的 Bug [#102](https://github.com/xCss/Valine/issues/102)

## v1.2.3, 2018-07-13

- `A` 新增评论内容可输入`HTML` 元素
- `U` 优化防`XSS` 逻辑
- `F` 修复当`UserAgent` 不存在时出现的`undefined` Bug

## v1.2.0-v1.2.2, 2018-07-09

- `A` 新增`Tab`快捷键
- `A` 新增 [GFM 任务列表](https://github.github.com/gfm/#task-list-items-extension-) ([marked#1250](https://github.com/markedjs/marked/pull/1250))
- `F` 修复`ul`、`ol`列表样式
- `F` 修复`新文章`不点击详情而`阅读量`为空的 Bug ([hexo-theme-next#345](https://github.com/theme-next/hexo-theme-next/pull/345#issuecomment-403285823))

## v1.2.0-beta2, 2018-07-08

- `F` 修复`blockquote`元素无样式的 Bug
- `F` 修复`pathname`为中文时可能出现访问量不统计的 Bug

## v1.2.0-beta1, 2018-07-07

- `A` 新增前端`xss`防御解决方案
- `A` 新增[文章阅读量统计](/visitor.html) 
- `A` 新增评论框高度随内容自动变化 ( by [autosize](https://github.com/jackmoore/autosize) )
- `U` 缩小`子评论`头像大小

## v1.2.0-beta, 2018-06-30

- `U` 修改子评论查询方式，减少80%的查询次数
- `F` 修复 `rid` 为 `空字符串` 时数据被忽略的 Bug [#95](https://github.com/xCss/Valine/issues/95)

## v1.1.9-rc3-v1.1.9, 2018-06-24

- `A` 新的Emoji列表
- `A` 新增快捷表情输入 `:smile: => 😄`  [√Emoji 对应表](https://github.com/xCss/Valine/blob/master/dist/plugins/emojis/light.json)
- `U` 优化样式
- `U` 修改 `子评论` 展示方式
- `U` 精简优化代码，缩减库大小
- `F` 修复页面中出现的 `Error 99` 错误 [#93](https://github.com/xCss/Valine/issues/93) 
- `F` 修复某些网页中可能出现 `section` 样式被重写的问题\

## v1.1.9-rc2, 2018-06-15

- `A` 新增对 `MathJax` 的支持 [#67](https://github.com/xCss/Valine/issues/67) 
- `U` 更新 `init()` 逻辑
- `U` 更新 `init()` 状态值
- `F` 修复评论区变成数字的 Bug [#89](https://github.com/xCss/Valine/issues/89) 
- `F` 修复评论列表中日期出现 `undefined` 的 Bug


## v1.1.9-rc1, 2018-06-15

...

## v1.1.9-beta9, 2018-03-29

- `F` 修复 `location.href` 中含中文时出现的评论刷新消失的Bug

更多[更新日志 >](https://github.com/xCss/Valine/releases)