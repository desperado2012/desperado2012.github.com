---
layout: post
category : tech
tags : [how-to, blog]
---
{% include JB/setup %}

好吧，算是我一时冲动自己弄了个博客。但还好，这种简介的风格确实是我的个性，正如别人介绍的，markdown这种写作方式能够让人专注眼前的内容而不是花哨的排版。尤其是可以在Sublime或者Notepad++里面直接写东西的感觉实在是太cool了，好感顿时就被激发了。在自己搭博客的过程中难免碰到各种恶心的状况，还好一遍下来也算是梳理了一下机子上的开发环境。从头开始。

## Git & Github ##

注册Github其实有不短的一段时间了，但是除了刚开始注册时用过几次，就束之高阁了。看到这一篇[如何高效利用GitHub](http://www.yangzhiping.com/tech/github.html)让我决定静下心来好好接触一下Github。之前git的配置还是比较顺利的，但是使用方面基本是零基础。还好，还有svn的那点儿底子。

    //准备工作，生成密钥并导入Github
    ssh-keygen -t rsa -C "xxx@gmail.com"
    
    //初始化目录
    git init
    
    //添加文件到git
    git add .
    
    //提交
    git commit -a -m 'blahblahblah...'
    
    //与github关联
    git remote add origin git@github.com:desperado2012/desperado2012.github.com.git
    
    //作为master提交到github
    git push origin master

嗯，目前我就只用到了这种程度，更多的命令和操作有待慢慢练习，看过的帖子有[git使用说明](http://www.cnblogs.com/welfear/archive/2010/05/24/1742614.html)和[Git和Github初次使用](http://www.linuxidc.com/Linux/2011-04/35036.htm)。

## [jekyll](http://baike.baidu.com/view/7878719.htm) & [markdown](http://baike.baidu.com/view/2311114.htm) ##

写这篇的时候，发现淘宝UED也出了篇介绍markdown的帖子[开始使用 Markdown](http://ued.taobao.com/blog/2012/07/03/getting-started-with-markdown/)，我终于潮了一把。只是装jekyll的时候，总是报错，只能老老实实的装了rvm，然后升级ruby果然就好了。

rvm的安装说明在这里，[RVM 安装与使用](http://www.cnblogs.com/orez88/articles/2270751.html)。

markdown的语法说明在这里，[Markdown 语法说明 (简体中文版)](http://wowubuntu.com/markdown/)。

jekyll的安装方法在这里，[使用Jekyll在Github上搭建博客](http://taberh.me/2011/12/26/use-Jekyll-build-Blog-on-Github.html)。

jekyll的官网在这里，[JB](http://jekyllbootstrap.com/)。

## Things to be continued ##

经过一番折腾，发现我把Mac上的开发环境搞乱了，一定要找个时间重装一下。重新梳理一下开发环境。

- Sublime
- Nginx, SVN, Git
- RVM, ruby, gem, jekyll, markdown
- qzz



