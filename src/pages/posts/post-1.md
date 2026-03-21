---
Layout: ../layouts/post.astro
title: '我的第一篇博客文章'
pubDate: 2026-03-11
description: '这是我的astro博客的第一篇文章。'
author: 'der骏'
image: 
    url: 'https://docs.astro.build/assets/rose.webp'
    alt: 'The Astro logo on a dark background with a pink glow.'
tags: ["astro","blogging","learning in public"]
---
<!-- 上面的是水平规则 -->
[首页](/)&nbsp;&nbsp;<!--使用空格实体-->
<span style="margin-right: 15px;">[关于](/about)</span>
<span style="margin-right: 15px;">[博客](/blog)</span>
<span style="margin-right: 15px;">[测试](/test)</span><!--使用span标签包裹利用style tag来实现右对齐像素-->
<br>
<style>
.nav-link {
	margin-right: 30px !important;
	text-decoration: none !important;
	color: #007bff !important;
	display: inline-block !important;
}
</style>

<a href="/" class="nav-link">首页</a>
<a href="/about" class="nav-link">关于</a>
<a href="/blog" class="nav-link">博客</a>
<a href="/test" class="nav-link">测试</a><!--通过在layout中定义类来全局生效-->
<hr><!--分界线-->
# 我的第一篇博客文章

发表于:2026-03-11

欢迎来到我学习关于 Astro 的新博客！在这里，我将分享我建立新网站的学习历程。

## 我做了什么
1. **安装astro**:首先，我创建了一个新的 Astro 项目并设置好了我的在线账号。<!-- **内容**这是加粗 -->
2. **制作页面**:然后我学习了如何通过创建新的 `.astro` <!-- `内容`这是代码-->文件并将它们保存在 `src/pages/` 文件夹里来制作页面。
3. **发表博客文章**:这是我的第一篇博客文章！我现在有用 Astro 编写的页面和用 Markdown 写的文章了！
4. **测试链接**:[Test link](/blog)<!-- 这是链接 粗体前面的是有序列表-->
5. **添加图片**:![A test image](/images/js练习.png)[^1]
[^1]: 这是图片的说明。<!-- 这是注脚 -->
<!-- 任务列表 -->
## 任务列表
- [x] 完成任务 1
- [ ] 完成任务 2
- [ ] 完成任务 3
## 表情符号(貌似没用 悲:(   )
That is so funny! :joy:
## 代码块
```js
console.log("Hello, world!");
```
## 高亮(依旧没用)
I need to highlight these ==very important words==.
## 角标
H~2~O<br>
2^2^

## 下一步计划

我将完成 Astro 教程，然后继续编写更多内容。关注我以获取更多信息。