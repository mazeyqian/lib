# cdn

⚠️ Note: The project folders have been cleared, and there is the configuration of Nginx to be compatible with archived assets.

```
location ~* ^\/cdn\/(jquery-2\.1\.1\.min\.js|bootstrap-3\.4\.1\/js\/bootstrap\.min\.js|vue-2\.6\.12\.min\.js)$ {
    try_files $uri /archived-cdn/$1 /cdn/index.js;
}
```

**Table of Contents**

- [cdn](#cdn)
  - [Install](#install)
  - [jQuery](#jquery)
  - [Lodash](#lodash)
  - [Vue 2.x](#vue-2x)
  - [Font Awesome](#font-awesome)
  - [Bootstrap](#bootstrap)
  - [Layer](#layer)
  - [IE 兼容](#ie-兼容)
  - [Confluence](#confluence)
  - [Mazey](#mazey)
  - [Tiny](#tiny)
  - [vConsole](#vconsole)

## Install

```
git clone https://github.com/mazeyqian/lib.git
```

<!-- Page - Begin -->

## jQuery

链接：https://i.mazey.net/lib/jquery/2.1.1/jquery.min.js

代码：

```
<script type="text/javascript" src="//i.mazey.net/lib/jquery/2.1.1/jquery.min.js"></script>
```

英文官方文档：https://api.jquery.com/

中文非官方文档：https://jquery.cuishifeng.cn/

## Lodash

链接：https://i.mazey.net/lib/lodash/4.17.21/lodash.min.js

代码：

```
<script type="text/javascript" src="//i.mazey.net/lib/lodash/4.17.21/lodash.min.js"></script>
```

英文官方文档：https://lodash.com/

中文非官方文档：https://www.lodashjs.com/

## Vue 2.x

链接：https://i.mazey.net/lib/vue/2.6.12/vue.min.js

代码：

```
<script type="text/javascript" src="//i.mazey.net/lib/vue/2.6.12/vue.min.js"></script>
```

官方文档：https://v2.cn.vuejs.org/

## Font Awesome

CSS 链接：https://i.mazey.net/lib/fontawesome/5.15.4/css/all.css

代码：

```
<link type="text/css" href="//i.mazey.net/lib/fontawesome/5.15.4/css/all.css" rel="stylesheet" />
```

官方文档：https://fontawesome.com/

## Bootstrap

CSS 链接：https://i.mazey.net/lib/bootstrap/3.4.1/css/bootstrap.min.css

JavaScript 链接：https://i.mazey.net/lib/bootstrap/3.4.1/js/bootstrap.min.js

代码：

```
<link type="text/css" href="//i.mazey.net/lib/bootstrap/3.4.1/css/bootstrap.min.css" rel="stylesheet" />

<script type="text/javascript" src="//i.mazey.net/lib/bootstrap/3.4.1/js/bootstrap.min.js"></script>
```

英文官方文档：https://getbootstrap.com/docs/3.4/

中文非官方文档：https://v3.bootcss.com/

## Layer

PC 链接：https://i.mazey.net/lib/layer/layer.js

代码：

```
<script type="text/javascript" src="//i.mazey.net/lib/layer/layer.js"></script>
```

Layer 中文非官方文档：https://layui.gitee.io/v2/docs/modules/layer.html

---

Mobile 链接：https://i.mazey.net/lib/layer/mobile/layer.js

代码：

```
<script type="text/javascript" src="//i.mazey.net/lib/layer/mobile/layer.js"></script>
```

Layer For Mobile 文档：https://www.layui.site/layer/mobile/api.html

## IE 兼容

IE 支持 HTML5：https://i.mazey.net/lib/html5shiv/3.7.3/html5shiv.min.js

IE 支持 CSS3：https://i.mazey.net/lib/respond/1.4.2/respond.min.js

代码：

```
<!--[if lt IE 9]>
      <script src="//i.mazey.net/lib/html5shiv/3.7.3/html5shiv.min.js"></script>
      <script src="//i.mazey.net/lib/respond/1.4.2/respond.min.js"></script>
<![endif]-->
```

## Confluence

CSS 链接：https://i.mazey.net/mazey-style/lib/confluence.css

JavaScript 链接：https://i.mazey.net/mazey-style/lib/confluence.js

代码：

```
<link type="text/css" href="//i.mazey.net/mazey-style/lib/confluence.css" rel="stylesheet" />

<script type="text/javascript" src="//i.mazey.net/mazey-style/lib/confluence.js"></script>
```

## Mazey

JavaScript 链接：https://i.mazey.net/lib/mazey/3.5.1/mazey.min.js

代码：

```
<script type="text/javascript" src="//i.mazey.net/lib/mazey/3.5.1/mazey.min.js"></script>
```

官方文档：https://i.mazey.net/mazey/docs/t.html

## Tiny

CSS 链接：https://i.mazey.net/polestar/lib/tiny.css

JavaScript 链接：https://i.mazey.net/polestar/lib/tiny.js

代码：

```
<link type="text/css" href="//i.mazey.net/polestar/lib/tiny.css" rel="stylesheet" />

<script type="text/javascript" src="//i.mazey.net/polestar/lib/tiny.js"></script>
```

## vConsole

JavaScript 链接：https://unpkg.com/vconsole@latest/dist/vconsole.min.js

代码：

```
<script src="//unpkg.com/vconsole@latest/dist/vconsole.min.js"></script>
<script>
  // VConsole will be exported to `window.VConsole` by default.
  if (window.VConsole) {
    var vConsole = new window.VConsole();
  }
</script>
```

官方文档：https://github.com/Tencent/vConsole

**附录**

本文档地址：[https://blog.mazey.net/cdn](https://blog.mazey.net/cdn)

<!-- Page - End -->
