---
layout: home
title: GitBook
permalink: /
---

这是一个[GitBook][2]样式的Jekyll站点，主要用来记录我学习Photoshop过程中的零散知识点，如果用一般的样式来呈现，会非常难以辨别和索引这些零碎的知识点，对我这个初学者来说，[GitBook][2]样式完美解决了这些问题，这是我非常喜欢的。

[GitBook][2]是一种优秀的网页前端风格，非常适合用于展示和组织书籍章节、博客等内容。

在 [Github Pages][1] 上部署[GitBook][2]的典型方法是：在本地构建HTML文件，然后将其推送到Github仓库（通常是gh-pages分支）。然而，重复这一流程相当繁琐，而且由于需要将生成的HTML文件暂存（stage）或移出，这也给使用Git进行版本控制带来了困难。

这个主题将样式定义从生成的[GitBook][2]网站中剥离出来，并为Jekyll提供了渲染模板。这样,Jekyll就可以直接将Markdown文档渲染成HTML。因此，整个网站可以直接部署到[Github Pages][1]，不必在每次源仓库内容变更后都重新生成并上传 HTML 文件包了。

[1]: https://pages.github.com
[2]: https://github.com/sighingnow/jekyll-gitbook

