# console-helper（日志小助手）

**console helper** — 旨在帮助开发人员编码时更快的输入/移除 log，搭配上醒目的主题，提高开发效率。

## 安装插件

安装插件：[VisualStudio - Marketplace](https://marketplace.visualstudio.com/items?itemName=AT-9420.console-helper)，VSCode 最低版本要求： `v1.51.0+`

## Feature

* [x] 快捷输出 log
* [x] 快捷删除当前页面中所有 log
* [x] 支持代码片段
* [x] 自定义前缀标识
* [x] 自定义字体颜色
* [x] 自定义背景颜色
* [x] 自定义字号大小
* [x] 可配置末尾是否加分号(默认不加)

## Usages

### 在当前行输出

> 在当前行输出 `console.log('[  ]', )` 语句，光标聚焦在输入位置，输入变量即可。

![insert](https://qn.xiesz.com/AT/insert.gif)

快捷方式：

* macOS: `cmd` + `shift` + `l`
* Windows: `ctrl` + `l`

### 将选中的变量打印

> 选中变量后按下快捷键，会在代码下方插入一行带颜色的 `console` 语句

![select-insert](https://qn.xiesz.com/AT/select-insert.gif)

快捷方式：

* macOS: `cmd` + `shift` + `l`
* Windows: `ctrl` + `l`

### 快捷删除当前页面中所有 log

> 删除页面上所有 `log` ，删除后窗口右下角会提示一共删除了几条 `console.log` 语句

![delete-all-log](https://qn.xiesz.com/AT/delete-all-log.gif)

快捷方式：

* macOS: `cmd` + `shift` + `d`
* Windows: `ctrl` + `shift` + `d`

### 代码片段

* `clg` or `log` 输出 `console.log('[ ] >', )`

![snippet-log](https://qn.xiesz.com/AT/snippet-log.gif)

* `clog` 输出 `console.log('%c[ ]: ', 'color: #bf2c9f; background: pink; font-size: 13px;', '')`

![snippet-clog](https://qn.xiesz.com/AT/snippet-clog.gif)

### 配置项

> 自定义小助手 console

![settings](https://qn.xiesz.com/AT/settings.gif)

* macOS: Code > 首选项 > 设置 > 输入 **日志小助手/wxConsole**，可自定义配置项。
* Windows: 文件 > 首选项 > 设置 > 输入 **日志小助手/wxConsole**，可自定义配置项。

## 修改快捷键绑定

> 修改快捷绑定(教程)

* macOS: Code > 首选项 > 键盘快捷方式 > 输入 **console-helper**，将默认 **cmd + shift + l** 改为习惯的快捷键即可，推荐使用 **cmd + l**。
* Windows: 文件 > 首选项 > 键盘快捷方式 > 输入 **console-helper**，将默认 **ctrl + l** 改为习惯的快捷键即可。

> 快速打开键盘快捷方式(快捷键)

* macOS: `cmd` + `k`,  `cmd` + `s`
* Windows: `ctrl` + `k`,  `ctrl` + `s`

## Changelog

[CHANGELOG](./CHANGELOG.md)

## License

[LICENSE](./LICENSE)
