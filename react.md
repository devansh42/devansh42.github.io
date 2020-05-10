---
layout: default
nav_order: 5
title: Deploying a React App for Free
---
# Deploying a React App for Free as Single Page Application

![React Log](//create-react-app.dev/img/logo.svg)

In this tutorial, I am going to show you guys, How to make a react app and deploy it on GStatic for free

#### Step 1
Install the **create-react-app** command utility by *Facebook*, this will help you to make Robust React App
```bash
    npm i -g create-react-app 
```
Above command will install create-react-app globally on your system.

#### Step 2
Create a React Project to deploy
```bash
    create-react-app demp-app   
```
Above command will install all the dependency for your project and will provide a basic react project files.

#### Step 3
After to make necessary changes to your project, its time to build it.
```bash
    npm run build   
```
Above will build the project and will put the optimized source in new created 'build' directory

#### Step 4
Install GStatic Command Cli on you system, for detailed installation guide, visit [here](install.html)
```bash
    npm i -g yu-gstatic
```        
#### Step 5
Authenticate your self with following command, for detailed Authentication guide, visit [here](auth.html)
```bash
    gstatic login  
```    
Or use `gstatic signup` if don't have an account

#### Step 6
Change to the production directory, in our case its *build*
```bash
    cd build
```

#### Step 7
Upload your project with your desired domain name as [SPA](//en.wikipedia.org/wiki/Single-page_application),
```bash
    gstatic up react-demo.gstatic.tech spa
```    
That's it, You just deployed your react project for free on GStatic, Share your project with your friends.

