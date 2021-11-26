# koishi-plugin-rss
 
[![npm](https://img.shields.io/npm/v/koishi-plugin-rss?style=flat-square)](https://www.npmjs.com/package/koishi-plugin-rss)

适用于 Koishi v4 的 RSS 订阅插件。

**注意：要使用本插件，你需要安装数据库支持。**

## 指令：rss

订阅或取消订阅 RSS。

- 基本语法：`rss <url>`
- 选项列表：
  - `-l, --list` 查看订阅列表
  - `-r, --remove` 取消订阅

## 配置项

### timeout

- 类型: `number`
- 默认值: `10000`

连接等待时间，单位为毫秒。

### refresh

- 类型: `number`
- 默认值: `60000`

内容刷新的时间间隔，单位为毫秒。

### userAgent

- 类型: `string`

连接 RSS 源所用的 User Agent。
