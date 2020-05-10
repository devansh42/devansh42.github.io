---
title: Updating Site Content
layout: default
nav_order: 7
---

## Background
Suppose you have a website hosted at [my-site.gstatic.tech](#) and you want to update that site, let's assume that *index.html* look like
```html
    <!doctype html>
    <html>
        <head>
            <title>My-Site</title>
            <!-- Some Meta Tags here -->
        </head>
        <body>
            <h1>Hello World!!</h1>
        </body>
    </html>

```
and you changed the *index.html* to this,
```html
    <!doctype html>
    <html>
        <head>
            <title>My-Site</title>
            <!-- Some Meta Tags here -->
        </head>
        <body>
            <h1>Hola World!!</h1>
            <h2>It's a new Day, Make it yours</h2>
        </body>
    </html>

```
after making nessacary changes, just run following command
```sh
    gstatic down my-site.gstatic.tech
```
Above command will undeploy your site,run the following command in the directory *containing your site file*
```sh
    gstatic up my-site.gstatic.tech

    # Or run
    # gstatic up my-site.gstatic.tech spa 
    # incase it's a Single Page Application
```
### What about site downtime
**Don't Worry** the downtime will be insignificant if you run the commands without any delay, so run second command just after the first one