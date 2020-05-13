---
layout: single
title: Installing GStatic Cli on Windows
sidebar:
    nav: "docs"
---

## Installing NodeJs on your PC

If you already have NodeJS installed on your system, skip this segement.

### Step 1
Download the NodeJS installer for windows from [here](https://nodejs.org/en/download/)

![](/img/docs/install/windows.png)

## Installing Gstatic Cli

### Step 1
Run the following command in *Command Prompt* to install gstatic-cli globally on your system
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
