---
layout: single
nav_order: 2
title: Installing GStatic Cli on Linux
sidebar:
    nav: "docs"
---

## Installing NodeJs on your PC

If you already have NodeJS installed on your system, skip this segement.

### Step 1
Run the following command in your terminal, you need root permission to do this task
```bash
    curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
    sudo apt-get install -y nodejs
```

## Installing Gstatic Cli

### Step 1
Run the following command in terminal to install gstatic-cli globally on your system
```bash
    npm i -g yu-gstatic
```
If you don't want to install it globally and just for a specific project, run the following command inside that project directory
```bash
    npm i yu-gstatic
```
and you can access gstatic cli with 
```bash
    npx gstatic some_command
```
