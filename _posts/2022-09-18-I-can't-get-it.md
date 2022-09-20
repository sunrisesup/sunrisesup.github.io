---
layout: post
title:  看不懂但大受震撼
tags: [JPG, 看不懂]
---

![img](https://github.com/sunrisesup/sunrisesup.github.io/raw/main/images/cannotgetit.JPG)

### 这是一个通过Jekyll在github建博客后，如何引用图片的例子。原理即使用Github作为图床在博文中插入图片，具体如下：
1. 在博客根目录下创建一个储存图片的文件夹images（或任何名字）
2. 把需要插入的图片保存到images文件夹里并push到github远程仓库，在github仓库中打开图片，复制url，如 https://github.com/sunrisesup/sunrisesup.github.io/blob/main/images/cannotgetit.JPG
3. 将URL中blob替换为raw，即 https://github.com/sunrisesup/sunrisesup.github.io/raw/main/images/cannotgetit.JPG
4. 使用markdown插入图片的语法即可显示图片，如：
<code>![img](https://github.com/sunrisesup/sunrisesup.github.io/raw/main/images/cannotgetit.JPG)</code>