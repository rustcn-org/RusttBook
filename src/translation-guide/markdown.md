# Markdown 和 HTML
我们使用的是 `GitHub Flavored Markdown` 简称 `GFM`，Github 全站都对该语法进行了支持。并且 `GFM` 还支持一些 HTML 语法，在本文档中也一并列出。

> `GFM` 的完整文档可以在 [Github 官方文档](https://docs.github.com/cn/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)中查看。



#### 引用图片

出于兼容性考虑，建议大家使用 `<img src="IMAGE_URL" />` 的方式引入图片，就目前所知，`![图片描述](IMAGE_URL)` 的方式在知乎、微信公众号上都无法正常使用。


#### 文字上标注

> 请勿随意使用该语法，它有几个缺点：
> 1. 跨平台支持性，有些平台可能无法识别这种语法，最终显示一大堆原始 mardown 文本
> 2. 让 Markdown 文档变得难以阅读和维护
> 
> **因此我们只推荐在如下情况才使用该语法：**
>
> 1. 该中文词汇绝大部分用户不知道或者不了解
> 2. 翻译者不确定自己翻译的是否正确( 在查询过指南的翻译词汇表后 )
>
> 总之，请尽量减少使用！甚至可以简单地用 `中午( Chinese )` 的方式来替代
```
<ruby>特征约束<rt>Trait Bound</rt></ruby>
```

<br />

<ruby>特征约束<rt>Trait Bound</rt></ruby>


#### 删除线

```
~~Mistaken text~~
```

<br />

~~Mistaken text~~


#### 表格对齐

```
| 左对齐  | 居中对齐  | 右对齐 |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |
```

<br />

| 左对齐  | 居中对齐  | 右对齐 |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |


#### 脚标

```
This is an example of a footnote[^note].

[^note]: This text is the contents of the footnote, which will be rendered
    towards the bottom.

```

This is an example of a footnote[^note].

[^note]: This text is the contents of the footnote, which will be rendered
    towards the bottom.


