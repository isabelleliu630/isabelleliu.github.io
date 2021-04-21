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


