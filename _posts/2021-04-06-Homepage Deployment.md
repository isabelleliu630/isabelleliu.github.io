---
title: '个人主页配置要点'
date: 2021-04-06
permalink: /posts/2021/04/Homepage Deployment/
tags:

  - Homepage

---
**Basis:** Github+AcademicPages+Jekyll 

-------

**Building procedures:**

1. Fork the Jekyll&AcademicPages [repository](https://github.com/academicpages/academicpages.github.io).
2. Go to the repository's settings and remane it to your own github name.
3. Change site-wide configuration in "_config.yml" and navigation bar settings in "_data/navigation.yml"
4. Uploade necessary linked files to the files/ directory. link with https://[your GitHub username].github.io/files/example.pdf.
5. Maintain with the following instructions. 

------

**Maintainance:** Write Markdown files (.md) in following folders or pages and then push to github with following instructions:  

1. git add . (There's a blank between "add" and ".".)  
2. git commit -m "Any title"  
3. git push -u origin master
4. 【如果在github网页版操作过，本地push不上去怎么办？】在以上三步之前加一句 git pull origin master实现本地和云端的同步。

-----------------

**.md file Edit:** 

1. Grammar check [this link](https://blog.csdn.net/qcx321/article/details/53780672).
2. Font color check [this link](https://blog.csdn.net/qq_43732429/article/details/108034518).

----------------------------

**Some questions:**

1. Why does the link always time out after inputting "git push"?  
    A: Several possible reasons:
- Network condition is too bad.  
- Use the following instructions to check your identity:  
git config user.name "yourname"  
git config user.email "youremail"  
- Try one more time (VPN problem)
- Check the integrity of the direction of push and your target repository
2. In Markdown grammar, \<font\> and \*\* cannot be used together cause they are from two different grammar systems.

3. 插入图片的时候，图片加载不出来怎么办：

   不要复制github里图片的链接，建议在github中打开图片之后直接右键点击复制图片，粘贴进markdown里面的带raw字段的地址是可以加载的。无论是插入还是外部链接都要采用这个方式。

   

   ----

   作者：刘雨桐

   出处：https://isabelleliu630.github.io//posts/2021/04/Homepage%20Deployment/

   本文版权归作者所有，未经作者同意必须在文章页面给出原文链接，否则保留追究法律责任的权利。


