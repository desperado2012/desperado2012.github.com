---
layout: post
category : tech
tags : [how-to, blog]
---
{% include JB/setup %}

好吧，算是我一时冲动自己弄了个博客。但还好，这种简介的风格确实是我的个性，正如别人介绍的，markdown这种写作方式能够让人专注眼前的内容而不是花哨的排版。尤其是可以在Sublime或者Notepad++里面直接写东西的感觉实在是太cool了，好感顿时就被激发了。在自己搭博客的过程中难免碰到各种恶心的状况，还好一遍下来也算是梳理了一下机子上的开发环境。从头开始。

## Git & Github ##

注册Github其实有不短的一段时间了，但是除了刚开始注册时用过几次，就束之高阁了。看到这一篇[如何高效利用GitHub](http://www.yangzhiping.com/tech/github.html)让我决定静下心来好好接触一下Github。之前git的配置还是比较顺利的，但是使用方面基本是零基础。还好，还有svn的那点儿底子。

    //准备工作，生成密钥导入Github
    
    //准备工作
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

嗯，目前我就只用到了这种程度，更多的命令和操作有待慢慢练习，

## jekyll & markdown ##


