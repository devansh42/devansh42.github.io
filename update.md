---
layout: single
nav_order: 7
title: Updating Site Content
---

# Updating Site Content

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
![Page before Edit](/img/update_before.png)
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
after making nessacary changes 
### Step 1
Just run following command
```sh
    gstatic down my-site.gstatic.tech
```
Above command will undeploy your site.
### Step 2
Run the following command in the directory *containing your site file*
```sh
    gstatic up my-site.gstatic.tech

    # Or run
    # gstatic up my-site.gstatic.tech spa 
    # incase it's a Single Page Application
```
![Page before Edit](/img/update_after.png)
### Hey! What about my site downtime
**Don't Worry** the downtime will be insignificant if you run the commands without any delay, so run second command immedatly after the first one.