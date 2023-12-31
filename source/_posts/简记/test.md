---
title: Hello Fluid
date: 2023-07-01 19:37
index_img: https://rmt.dogedoge.com/fetch/fluid/storage/hello-fluid/cover.png?w=480&fmt=webp
tags:
  - test
math: true
mermaid: true
archive: false
password: hello
message: password is "hello"
updated: 2023-10-14 18:45
---

> 欢迎体验 [Fluid](https://github.com/fluid-dev/hexo-theme-fluid) ，这是一款 Material Design 风格的 Hexo 主题，以简约的设计帮助你专注于写作，本篇文章可预览主题的样式及功能。

<!-- more -->

## some tests
### 脚注

以下是脚注演示[^1]：

如果你有 Fluid 主题或 Hexo 博客相关的文章，可以通过 Pull Request 方式投稿[^2]。

footnote test[^note]

[^1]: 脚注演示
[^2]: 投稿具体详见[https://github.com/fluid-dev/hexo-fluid-blog](https://github.com/fluid-dev/hexo-fluid-blog)

[^note]: another note
  multi-line footnote
### note
<div class="alert alert-success"> This is a success box, color = green </div>
<div class="alert alert-info"> This is an info box, color = blue </div>
<div class="alert alert-warning"> This is a warning box, color = orange </div>
<div class="alert alert-danger"> This is a danger box, color = red </div>

> [!NOTE]
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]
> Crucial information necessary for users to succeed.

> [!WARNING]
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.

### 首行空格。

&emsp;&emsp;测试 `$emsp;`

&nbsp;另一个空格`&nbsp;`

### links

{% post_link 简记/test 'code/test' %}
{% post_link 简记/test 'try test' %}

blog连接
[test party](/hexo/简记/party)
[test other](/hexo/杂谈/Barbie)
pictures连接

![纳斯塔霞](/hexoimg/idiot03.png)



### html tags

<span>test span tag</span>

<ins>test ins</ins>

<details> <summary>summary</summary>
then we well have some shitty words here. test some thing.
</details>

<p class="note note-primary">
note-primary
</p>
<p class="note note-info">
note-info
</p>
<p class="note note-warning">
note-warning
</p>
<p class="note note-danger">
note-danger
</p>

用html语法<span class="label label-primary"> 实现行内 </span>，具体来说是'<span>' tag。

## 文字

文章大部分使用的是 github-markdown 样式，并加入了一些 Material 风格。

### H3 标题

#### H4 标题

**粗体**

_斜体_



## 表格

| Header 1 | Header 2 | Header 3  |
| -------- | -------- | --------- |
| Key 1    | Value 1  | Comment 1 |
| Key 2    | Value 2  | Comment 2 |
| Key 3    | Value 3  | Comment 3 |

## 列表

### 有序列表

Fluid 相较于其他主题的优势：

1. 设计遵循简洁至上，同时具有轻快的体验，和优雅的颜值；
2. 提供大量定制化配置项，使每个用户使用该主题都能具有独特的样式；
3. 响应式页面，适配手机、平板等设备；

### 无序列表

Fluid 功能特性：

- 图片懒加载
- 自定义代码高亮方案
- 内置多语言
- 支持多款评论插件
- 支持使用数据文件存放配置
- 自定义静态资源 CDN
- 内置文章搜索
- 页脚备案信息
- 网页访问统计
- 支持 LaTeX 数学公式
- 支持 mermaid 流程图
- 音乐播放器

## 图片

![](https://rmt.dogedoge.com/fetch/fluid/storage/post.png?w=1280&fmt=webp)

## LaTex

基于 MathJax 引擎：

$$
\Gamma _ { \epsilon } ( x ) = [ 1- e ^ { - 2\pi \epsilon } ] ^ { 1- x } \prod _ { n = 0} ^ { \infty } \frac { 1- \operatorname{exp} ( - 2\pi \epsilon ( n + 1) ) } { 1- \operatorname{exp} ( - 2\pi \epsilon ( x + n ) ) }
$$

$$
\left( \begin{array} c t ^ { \prime } \\ x ^ { \prime } \\ y ^ { \prime } \\ z ^ { \prime } \end{array} \right) = \left( \begin{array} { c c c c } { \gamma } & { - \gamma \beta } & { 0 } & { 0 } \\ { - \gamma \beta } & { \gamma } & { 0 } & { 0 } \\ { 0 } & { 0 } & { 1 } & { 0 } \\ { 0 } & { 0 } & { 0 } & { 1 } \end{array} \right) \left( \begin{array} c t \\ x \\ y \\ z \end{array} \right)
$$

$$
6 \mathrm { CO } _ { 2 } + 6 \mathrm { H } _ { 2 } \mathrm { O } \rightarrow \mathrm { C } _ { 6 } \mathrm { H } _ { 12 } \mathrm { O } _ { 6 } + 6 \mathrm { O } _ { 2 }
$$

## 流程图

基于 mermaid 语法：

```mermaid
sequenceDiagram
participant Alice
participant Bob
Alice->>John: Hello John, how are you?
loop Healthcheck
    John->>John: Fight against hypochondria
end
Note right of John: Rational thoughts <br/>prevail...
John-->>Alice: Great!
John->>Bob: How about you?
Bob-->>John: Jolly good!
```

```mermaid
gantt
dateFormat  YYYY-MM-DD
title Adding GANTT diagram to mermaid

section A section
Completed task            :done,    des1, 2014-01-06,2014-01-08
Active task               :active,  des2, 2014-01-09, 3d
Future task               :         des3, after des2, 5d
Future task2               :         des4, after des3, 5d
```

```mermaid
classDiagram
Class01 <|-- AveryLongClass : Cool
Class03 *-- Class04
Class05 o-- Class06
Class07 .. Class08
Class09 --> C2 : Where am i?
Class09 --* C3
Class09 --|> Class07
Class07 : equals()
Class07 : Object[] elementData
Class01 : size()
Class01 : int chimp
Class01 : int gorilla
Class08 <--> C2: Cool label
```

## 内置 Tag 插件

内置了一些 Tag 插件，用于实现 Markdown 不容易生成的样式，具体使用方式请见 [用户指南](https://hexo.fluid-dev.com/docs/guide/#tag-%E6%8F%92%E4%BB%B6)。

### 行内标签

### 勾选框

{% cb 主要是解决一些 Renderer 不支持勾选, true %}

### 按钮

{% btn javascript:;, 支持链接 %}

### 组图

{% gi 5 3-2 %}
![](https://rmt.dogedoge.com/fetch/fluid/storage/hello-fluid/cover.png?w=480&fmt=webp)
![](https://rmt.dogedoge.com/fetch/fluid/storage/hello-fluid/cover.png?w=480&fmt=webp)
![](https://rmt.dogedoge.com/fetch/fluid/storage/hello-fluid/cover.png?w=480&fmt=webp)
![](https://rmt.dogedoge.com/fetch/fluid/storage/hello-fluid/cover.png?w=480&fmt=webp)
![](https://rmt.dogedoge.com/fetch/fluid/storage/hello-fluid/cover.png?w=480&fmt=webp)
{% endgi %}



### 愚人节：你的屏幕上有根头发

<script>
/***
 * 愚人节彩蛋 - 你屏幕上有根毛
 * 出处：https://www.baidu.com/s?ie=UTF-8&wd=%E6%84%9A%E4%BA%BA%E8%8A%82
 * 整理：mengkun https://mkblog.cn/
 */
!function() {
    var bottom = Math.floor(60 * Math.random()),
        right = Math.floor(50 * Math.random()),
        rotate = Math.floor(360 * Math.random());
    var foolsEgg = document.createElement("img");
    foolsEgg.src = "https://search-operate.cdn.bcebos.com/b028c278cbb84660f8bde79d819bc30b.png";
    foolsEgg.style.position = "fixed"; 
    foolsEgg.style.bottom = "".concat(bottom, "%");
    foolsEgg.style.right = "".concat(right, "%"); 
    foolsEgg.style.zIndex = "9999"; 
    foolsEgg.style.pointerEvents = "none";
    foolsEgg.style.width = "40%";
    foolsEgg.style.maxWidth = "190px";
    foolsEgg.style.transform = "".concat("rotate(", rotate, "deg)"); 
    document.body.append(foolsEgg);
} ();
</script>

```js
<script>
/***
 * 愚人节彩蛋 - 你屏幕上有根毛
 * 出处：https://www.baidu.com/s?ie=UTF-8&wd=%E6%84%9A%E4%BA%BA%E8%8A%82
 * 整理：mengkun https://mkblog.cn/
 */
!function() {
    var bottom = Math.floor(60 * Math.random()),
        right = Math.floor(50 * Math.random()),
        rotate = Math.floor(360 * Math.random());
    var foolsEgg = document.createElement("img");
    foolsEgg.src = "https://search-operate.cdn.bcebos.com/b028c278cbb84660f8bde79d819bc30b.png";
    foolsEgg.style.position = "fixed";
    foolsEgg.style.bottom = "".concat(bottom, "%");
    foolsEgg.style.right = "".concat(right, "%");
    foolsEgg.style.zIndex = "9999";
    foolsEgg.style.pointerEvents = "none";
    foolsEgg.style.width = "40%";
    foolsEgg.style.maxWidth = "190px";
    foolsEgg.style.transform = "".concat("rotate(", rotate, "deg)");
    document.body.append(foolsEgg);
} ();
</script>
```

