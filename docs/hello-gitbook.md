# 使用心得

## 背景

写代码写累了突然想博客，想到了已经半年不维护的WordPress博客，架设在VPS上，也有自己的域名，不过现在VPS没有续费已经过期.当时用的是Docker架设的WordPress，WordPress的文件在VPS上，本地总是不太方便修改，所以折腾的少，曾想研究[`WordPress.org`](https://wordpress.org)官网上的API，比较懒没有坚持下去.

## 需求

现在主要是想方便编辑，可Git，最好能和本地工作环境整合，比如VS Code，页面渲染简介漂亮，因为是拿来展示内容为主，于是就想起了GitBook，在学校时曾经了解过GitBook，奈何太忙就没有真正开始使用GitBook.现在用起来真的是觉得很方便.

## 心得

GitBook渲染出来的页面也很简洁很美观，是内容为主，主要展示的也是内容，没有无关的冗余，使用也非常简单(对于开发者来说)，与Git账户的仓库绑定后，在本地添加Git仓库，创建文件，跟踪文件，提交文件，就跟提交代码一样，符合开发者的使用习惯.Gittable的特性真的是太重要了.并且对Markdown文本的支持也很好，数学公式可以通过插件获得，目前支持KeTex和MathJax，[配置也很简单](https://gitbookio.gitbooks.io/documentation/format/math.html).图片的话也可以用Markdown语法描述，也是把图片复制到项目文件夹，然后在Markdown中用相对路径引用就可以了，比如`../assets/image1.png`这样，当然图片也要随Git提交到远程仓库才能在网页上显示出来.

## 后续

一直以来都幻想经营一个自己的博客，曾经安装过`WordPress`，以后可能会考虑自己用`Laravel`或者`SpringBoot`做个博客，不过那样的功能肯定比不上`WordPress`，但是起码能体会到创造的乐趣，就看什么时候有时间精力了.很多创造性的想法应该尽早地去验证，才能知道自己到底行不行.