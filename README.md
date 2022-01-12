# Xtiper

#### 介绍
Xtiper 是一款整合 PC 、移动端的弹层弹窗（甚至还有弹幕）解决方案。采用原生的 javascript 编写，体积小，不依赖任何 js 库，不加载任何图片，使用方便。

#### 预览地址
[https://ovsexia.github.io/xtiper/](https://ovsexia.github.io/xtiper/)

#### 从 npm 安装
`npm i xtiper`

#### 轻量版 xtiper.lite.js，去除了弹幕、相册、面板菜单，体积缩小为原版的40%

#### 使用方法

`<link href="css/xtiper.css" type="text/css" rel="stylesheet" />`

`<script src="js/xtiper.js" type="text/javascript"></script>`

### 版本更新

#### v2.7 发布：[下载](https://github.com/ovsexia/xtiper/releases/tag/v2.7.0)
1.open层新增成功回调函数

2.alert、confirm类型重新调整参数位置，避免混乱

3.alert、confirm新增了确认取消的回调函数

4.其他小bug修复

#### v2.6 正式版发布：[下载](https://github.com/ovsexia/xtiper/releases/tag/v2.6.6)
1. win层新增最大宽度，优化win层宽度为百分比时的位置

2. open层新增最大宽度和最大高度

3. open层新增reset属性，每次调用时可不重置内容

4. open层新增id属性，配合reset属性使用，可调用参数完全相同的多个实例

5. 其他bug修复

6. 优化弹幕层，窗口不活动时停止弹幕

#### v2.5
稳定版本版发布

#### v2.0-2.4
优化程序，修复bug

#### v2.0
代码重构，确定主要功能

#### v1.0
放飞自我，确定基本功能