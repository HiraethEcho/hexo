---
title: "redefine readme"
thumbnail: https://evan.beee.top/img/d00ebf818778f3aad141173167ad0e52-4c3d7.png
published: true
date: 2024-02-18 00:11
updated: 2024-02-18 00:11
tags:
  - test
---

# hexo-theme-redefine
此主题的一些显示效果

## 功能展示

### Note Large大号提示块

{% btn center large::Note Large大号提示块文档::https://redefine-docs.ohevan.com/modules/notes#%E5%A4%A7%E5%8F%B7%E6%8F%90%E7%A4%BA%E5%9D%97::fa-solid fa-book %}

{% notel default 信息 %}
换行测试
换行测试
换行测试
{% endnotel %}

{% notel blue 提示 %}
换行测试
换行测试
换行测试
{% endnotel %}

{% notel green 自定义标题 %}
换行测试
换行测试
换行测试
{% endnotel %}

{% notel yellow 自定义标题 %}
换行测试
换行测试
换行测试
{% endnotel %}

{% notel orange 自定义标题 %}
换行测试
换行测试
换行测试
{% endnotel %}

{% notel red 自定义标题 %}
换行测试
换行测试
换行测试
{% endnotel %}

### Note 小号提示块

{% btn center large::Note 小号提示块文档::https://redefine-docs.ohevan.com/modules/notes#%E5%B0%8F%E5%8F%B7%E6%8F%90%E7%A4%BA%E5%9D%97::fa-solid fa-book %}

{% note  %}
默认 提示块标签
{% endnote %}

{% note default  %}
default 提示块标签
{% endnote %}

{% note primary  %}
primary 提示块标签
{% endnote %}

{% note success  %}
success 提示块标签
{% endnote %}

{% note info  %}
info 提示块标签
{% endnote %}

{% note warning  %}
warning 提示块标签
{% endnote %}

{% note danger  %}
danger 提示块标签
{% endnote %}

{% note red fa-bolt%}
自定义提示块标签
{% endnote %}

### Folding 折叠模块

{% btn center large::Folding 折叠模块文档::https://redefine-docs.ohevan.com/modules/folding::fa-solid fa-book %}

{% folding yellow::Folding 测试： 点击查看更多 %}

{% note danger  %}
danger 提示块标签
{% endnote %}

{% note tip  %}
tip 提示块标签
{% endnote %}

{% endfolding %}

{% folding green::Folding 测试： 点击查看更多 %}

{% note danger  %}
danger 提示块标签
{% endnote %}

{% note tip  %}
tip 提示块标签
{% endnote %}

{% endfolding %}

{% folding blue::Folding 测试： 点击查看更多 %}

啊啊啊啊啊

{% note danger  %}
danger 提示块标签
{% endnote %}

{% note tip  %}
tip 提示块标签
{% endnote %}

{% endfolding %}

### Tabs 分栏模块

{% btn center large::Tabs 分栏模块文档::https://redefine-docs.ohevan.com/modules/tabs::fa-solid fa-book %}

{% tabs First unique name %}

<!-- tab First Tab-->

**This is Tab 1.**

<!-- endtab -->

<!-- tab Second Tab-->

**This is Tab 2.**

This is Tab 2.

<!-- endtab -->

<!-- tab Third Tab-->

**This is Tab 3.**

This is Tab 3.

This is Tab 3.

<!-- endtab -->

{% endtabs %}

### Button 按钮模块

不设置任何参数的 {% btn 按钮:: / %} 适合融入段落中。

regular 按钮适合独立于段落之外：

{% btn regular::示例博客::https://www.ohevan.com::fa-solid fa-play-circle %}

{% btn regular::示例博客::https://www.ohevan.com::fa-solid fa-play-circle %}

large 按钮更具有强调作用，建议搭配 center 使用：

{% btn center large::Button 按钮模块 开始使用::https://redefine-docs.ohevan.com/modules/buttons::fa-solid fa-book %}

### callouts

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

more

> [!TODO]

> [!bug]

> [!example]

> [!info]

> [!quote]

> [!cite]

> [!success]

> [!failure]

> [!question]

> [!help]

> [!attention]

> [!abstract]

- [ ] checkbox empty
- [-] checkbox on going
- [x] checkbox done

## 📄 文档

请阅读 [Redefine 主题官方文档](https://redefine-docs.ohevan.com/) 进行主题配置与安装，非常简单易懂。

同时，请查看 [Redefine 主题开发文档](https://redefine-docs.ohevan.com/developer)。

 官方演示站

- [EvanNotFound's Blog](https://ohevan.com)
- [Theme Redefine 演示站点](https://redefine.ohevan.com)
- [Redefine 用户墙](https://redefine.ohevan.com/showcase)

## ⛰️ 部分功能

- [笔记模块](https://redefine-docs.ohevan.com/modules/notes)
- [可自定义页脚](https://redefine-docs.ohevan.com/footer)
- [网站运行时间显示](https://redefine-docs.ohevan.com/footer#%E8%BF%90%E8%A1%8C%E6%97%B6%E9%97%B4)
- [文章头图](https://redefine-docs.ohevan.com/article_customize/banner)
- [Aplayer 音乐播放器支持](https://redefine-docs.ohevan.com/plugins/aplayer)
- [说说模块](https://redefine-docs.ohevan.com/shuoshuo)
- [自定义字体](https://redefine-docs.ohevan.com/basic/global#%E8%87%AA%E5%AE%9A%E4%B9%89%E5%AD%97%E4%BD%93)
