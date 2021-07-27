---
title: Home
date: 2016-01-01T00:00:00.000Z
permalink: /
wide: true
hideTitle: true
layout: layouts/base.njk
eleventyNavigation:
  key: Home
  order: 0
---
<style>
.header {
    background: linear-gradient(0deg, rgba(64,224,208,0) 0%, rgba(64,224,208,.7) 20%);
}
.header a[href], header a[href]:visited {
    color: #000a;
}
.header nav li a[data-current="current item"] {
    background-color: transparent;
    border-bottom: 5px solid yellow;
}
</style>
<img style="
    max-width: 100%;
    height: auto;
    position: absolute;
    width: 100%; top:0; filter: saturate(1.2);
    z-index: -1;" src="/static/img/hero.jpg">