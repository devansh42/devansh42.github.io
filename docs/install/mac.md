---
layout: single
title: Installing GStatic Cli on Mac-Os
sidebar:
    nav: "docs"
---

## Installing NodeJs on your PC

If you already have NodeJS installed on your system, skip this segement.

### Step 1
Download the NodeJS installer for Mac-Os from [here](https://nodejs.org/en/download/)

![](/img/docs/install/macos.png)
#### Note -
    If your are comfortable terminal user you can install nodejs from terminal also, read [this guide](https://nodejs.org/en/download/package-manager/#macos)


## Installing Gstatic Cli

### Step 1
Run the following command in *Terminal* to install gstatic-cli globally on your system
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
