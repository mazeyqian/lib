# lib

⚠️ Note: The project folders have been cleared, and there is the configuration of Nginx to be compatible with archived assets.

```
location ~* ^\/cdn\/(jquery-2\.1\.1\.min\.js|bootstrap-3\.4\.1\/js\/bootstrap\.min\.js|vue-2\.6\.12\.min\.js)$ {
    try_files $uri /archived-cdn/$1 /cdn/index.js;
}
```

**Table of Contents**

- [lib](#lib)
  - [Install](#install)
  - [jQuery](#jquery)
  - [Bootstrap](#bootstrap)
  - [Vue 2.x](#vue-2x)
  - [Vuex](#vuex)
  - [Layer](#layer)
  - [Swiper](#swiper)
  - [Lodash](#lodash)
  - [Axios](#axios)
  - [vConsole](#vconsole)
  - [Font Awesome](#font-awesome)
  - [IE 兼容](#ie-兼容)
  - [Sha1](#sha1)
  - [Mazey](#mazey)
  - [Confluence](#confluence)
  - [Tiny](#tiny)

## Install

```
git clone https://github.com/mazeyqian/lib.git
```

<!-- Page - Begin -->

## jQuery

链接：

- v2.1.1：https://i.mazey.net/lib/jquery/2.1.1/jquery.min.js
- v3.1.1：https://i.mazey.net/lib/jquery/3.1.1/jquery.min.js

代码：

```
<script type="text/javascript" src="//i.mazey.net/lib/jquery/2.1.1/jquery.min.js"></script>
```

英文官方文档：https://api.jquery.com/

中文非官方文档：https://jquery.cuishifeng.cn/

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

## Vue 2.x

链接：https://i.mazey.net/lib/vue/2.6.12/vue.min.js

代码：

```
<script type="text/javascript" src="//i.mazey.net/lib/vue/2.6.12/vue.min.js"></script>
```

官方文档：https://v2.cn.vuejs.org/

## Vuex

链接：https://i.mazey.net/lib/vuex/3.0.1/vuex.min.js

代码：

```
<script type="text/javascript" src="//i.mazey.net/lib/vuex/3.0.1/vuex.min.js"></script>
```

官方文档：https://v3.vuex.vuejs.org/zh/

## Layer

PC 链接：https://i.mazey.net/lib/layer/layer.js

代码：

```
<script type="text/javascript" src="//i.mazey.net/lib/layer/layer.js"></script>
```

非官方文档：https://layui.gitee.io/v2/docs/modules/layer.html

---

Mobile 链接：https://i.mazey.net/lib/layer/mobile/layer.js

代码：

```
<script type="text/javascript" src="//i.mazey.net/lib/layer/mobile/layer.js"></script>
```

非官方文档：https://www.layui.site/layer/mobile/api.html

## Swiper

CSS 链接：https://i.mazey.net/lib/swiper/9.3.2/swiper.min.css

JavaScript 链接：https://i.mazey.net/lib/swiper/9.3.2/swiper.min.js

代码：

```
<link type="text/css" href="//i.mazey.net/lib/swiper/9.3.2/swiper.min.css" rel="stylesheet" />
<script type="text/javascript" src="//i.mazey.net/lib/swiper/9.3.2/swiper.min.js"></script>
```

官方文档：https://swiperjs.com/get-started

## Lodash

链接：https://i.mazey.net/lib/lodash/4.17.21/lodash.min.js

代码：

```
<script type="text/javascript" src="//i.mazey.net/lib/lodash/4.17.21/lodash.min.js"></script>
```

英文官方文档：https://lodash.com/

中文非官方文档：https://www.lodashjs.com/

## Axios

链接：https://i.mazey.net/lib/axios/1.4.0/axios.min.js

代码：

```
<script type="text/javascript" src="//i.mazey.net/lib/axios/1.4.0/axios.min.js"></script>
```

官方文档：https://axios-http.com/docs/intro

## vConsole

JavaScript 链接：https://i.mazey.net/lib/vconsole/3.15.0/vconsole.min.js

代码：

```
<script src="//i.mazey.net/lib/vconsole/3.15.0/vconsole.min.js"></script>
<script>
  // VConsole will be exported to `window.VConsole` by default.
  if (window.VConsole) {
    var vConsole = new window.VConsole();
  }
</script>
```

官方文档：https://github.com/Tencent/vConsole

## Font Awesome

CSS 链接：https://i.mazey.net/lib/fontawesome/5.15.4/css/all.css

代码：

```
<link type="text/css" href="//i.mazey.net/lib/fontawesome/5.15.4/css/all.css" rel="stylesheet" />
```

官方文档：https://fontawesome.com/

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

## Sha1

JavaScript 链接：https://i.mazey.net/lib/encode/js-sha1/0.6.0/sha1.min.js

代码：

```
<script type="text/javascript" src="//i.mazey.net/lib/encode/js-sha1/0.6.0/sha1.min.js"></script>
```

官方文档：https://github.com/emn178/js-sha1

## Mazey

JavaScript 链接：https://i.mazey.net/lib/mazey/3.6.6/mazey.min.js

代码：

```
<script type="text/javascript" src="//i.mazey.net/lib/mazey/3.6.6/mazey.min.js"></script>
```

官方文档：https://i.mazey.net/mazey/docs/index.html

## Confluence

CSS 链接：https://i.mazey.net/style/lib/confluence.css

JavaScript 链接：https://i.mazey.net/polestar/lib/confluence.js

代码：

```
<link type="text/css" href="//i.mazey.net/style/lib/confluence.css" rel="stylesheet" />
<script type="text/javascript" src="//i.mazey.net/polestar/lib/confluence.js"></script>
```

## Tiny

CSS 链接：https://i.mazey.net/style/lib/tiny.css

JavaScript 链接：https://i.mazey.net/polestar/lib/tiny.js

代码：

```
<link type="text/css" href="//i.mazey.net/style/lib/tiny.css" rel="stylesheet" />
<script type="text/javascript" src="//i.mazey.net/polestar/lib/tiny.js"></script>
```

**附录**

本文档地址：[https://blog.mazey.net/cdn](https://blog.mazey.net/cdn)

<!-- Page - End -->
