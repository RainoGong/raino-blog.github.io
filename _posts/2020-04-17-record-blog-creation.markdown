---
layout:     post
title:      "记录blog搭建过程"
subtitle:   " \"只当作测试用\""
date:       2020-04-17 15:37
author:     "rainogong"
header-img: "img/tag-bg.jpg"
disqus_username: rainogong
tags:
    - 杂七杂八
---

> “Yeah It's on. ”  

## 经历

&emsp;&emsp;两年之前尝试着建立过一次blog，当时随便租用了vultr的$2.5的机器，一边做它用，一边顺便搭建了一个wordpress的blog。但是毕竟也是随便搭建的，也没有维护过，后来就没有续租vultr的机器，blog也就丢失了，上面也没发布有价值的内容。应为不需要专业的blog网站，这就需要找到一种简单，免费便捷的搭建方式。后来就选择了github page + freenom的域名 + cloudflare的DNS解析，这种flow来搭建，这种方法完全免费，不用担心自己的blog长时间不维护导致丢失等问题，只需要定期申请免费域名并更换。  

## 主题选择  
&emsp;&emsp;最开始没想到会能直接fork别人的仓库，想着用jekyll一点一点搭建，自己对这个语言也不懂，只能看基础教程一点一点学习。后来知道fork别人仓库的方法，变选择了一些来theme来创作，最终选择了huxpro的仓库，简介，代码开源。   
## 创建流程  
&emsp;&emsp;首先就是fork一个自己喜欢的blog仓库，开通GitHub page的选项  
![avatar](https://github.com/RainoGong/raino-blog.github.io/blob/master/img/2020-04/github-page-00.jpg?raw=true)
![avatar](https://github.com/RainoGong/raino-blog.github.io/blob/master/img/2020-04/github-page-01.jpg?raw=true)

这里的Enforce HTTPS选项由于一些不知道的原因不能点选  

然后配置cloudflare  域名解析，这里是比较关键的点  
![avatar](https://github.com/RainoGong/raino-blog.github.io/blob/master/img/2020-04/cloudflare-00.jpg?raw=true)


