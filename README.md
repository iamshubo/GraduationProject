# 项目概述
 
## 题目：基于textrank的摘要内容聚合推荐系统

## 背景  

<p word-wrap:break-word> 随着信息技术的发展，人们获取信息的途径逐渐由传统的纸质媒体转移到移动终端，但当前社会信息泛滥导致人们总是被动的接受信息，夸张的标题更是加大的人们获取有效信息的难度。而各大互联网内容聚合平台以经济效益为目的通过智能算法精准投放的内容使人们无法真正快速有效的获取自己想要的内容，本系统使用rss协议聚合信息为用户提供信息池，基于TF-IDF技术帮助用户初步筛选向用户推荐信息，并使用textrank内容摘要算法帮助人们快速有效的获取有效信息。</p>  
    
## 项目目标  

<p word-wrap:break-word>实现一个rss内容聚合平台向用户提供新闻信息，能够根据用户阅读历史向用户智能推荐信息，并为每篇文章生成阅读友好的摘要信息帮助用户筛选有效信息。</p>  


## 基本实现思想

### 1. 开发语言

使用python实现TF-IDF推荐和textrank内容摘要。使用java搭建平台。


### 2. 采用的技术或算法
    
基于内容的智能推荐技术：
<a href="https://baike.baidu.com/item/tf-idf/8816134?fr=aladdin">TF-IDF（term frequency–inverse document frequency）</a>

文本摘要生成算法：
<a href="https://www.cnblogs.com/xueyinzhe/p/7101295.html">textrank关键字及摘要生成算法</a>
    

