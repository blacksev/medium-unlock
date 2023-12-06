# Medium Unlock
[English](https://github.com/blacksev/medium-unlock) | [中文](https://github.com/blacksev/medium-unlock/blob/main/README-zh.md)
___
自动检测Medium文章（包括子域名和自定义域名），替换URL为readmedium.com来解锁Medium付费文章
## 安装脚本
首先需要安装一个用户脚本管理器,根据当前使用的浏览器来[选择一个用户脚本管理器](https://greasyfork.org/zh-CN)。

[Medium 解锁](https://greasyfork.org/zh-CN/scripts/457837-medium%E8%A7%A3%E9%94%81)页面点击安装，或者直接复制main.js的全部内容手动添加脚本。

### Via浏览器
兼容[Via浏览器](https://viayoo.com/)，移动端用户可使用via浏览器，手动复制main.js的全部内容添加脚本。
## 使用方法
点击文章页面出现的绿色悬浮球
## 插件原理
[readmedium.com](https://readmedium.com)

判断当前页是否为Medium文章，按照readmedium.com提供的方案替换url，通过访问readmedium.com来获得全文。

readmedium.com官方给出的自动化替换URL方式为[LibRedirect](https://libredirect.codeberg.page/)，但是在实际使用过程中体验不太好。

## 支持网站
- [Medium](https://medium.com)
  - medium.com
  - *.medium.com
    - james.medium.com
    - robert.medium.com
    - ...
  - custom domains
    - entrepreneurshandbook.co
    - ...

## 屏幕截图
![](https://raw.githubusercontent.com/blacksev/medium-unlock/main/image/example-pc.png)
![](https://raw.githubusercontent.com/blacksev/medium-unlock/main/image/example-mobile.png)

## LICENSE
[MIT LICENSE](https://mit-license.org/)

## Github
[medium-unlock](https://github.com/blacksev/medium-unlock)

## Greasyfork
[Medium Unlock](https://greasyfork.org/scripts/457837-medium%E8%A7%A3%E9%94%81)