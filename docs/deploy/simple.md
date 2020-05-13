---
layout: single
nav_order: 4
title: Hosting a Simple HTML/CSS/JS Site
sidebar:
    nav: "docs"
---

In this tutorial will learn how to host a simple html based website on GStatic.
Assuming you already have [installed](/docs/install/windows.html) Gstatic cli and [authenticated](/docs/auth/login.html) yourself.

Let's we have a folder named *my-simple-site* containing our website files.
![Files in Folder](/img/docs/deploy/simple_tree.png)

1. Change to the directory having website files
```bash
    cd my-simple-site
```
![Changing the directory](/img/docs/deploy/simple_cd.png)


2. Upload your project with your desired domain name  
```bash
    gstatic up my-simple-site.gstatic.tech 
```    
![Deploying the Website](/img/docs/deploy/simple.png)


That's it, You just deployed your html based project for free on GStatic, Share your project with your friends [my-simple-site.gstatic.tech](https://my-simple-site.gstatic.tech)

