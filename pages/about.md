---
layout: page
title: About
description: 学习使我快乐
keywords: Acforme
comments: true
menu: 关于
permalink: /about/
---

学习使我快乐。

## 坚信

* 努力

## 联系

* GitHub：
* 掘金：
* LinkedIn：
* 博客：
* 微博: 
* 知乎: 
* 豆瓣: 

## Skill Keywords

#### Software Engineer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_software_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### Mobile Developer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_mobile_app_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### Windows Developer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_windows_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>
