---
title: "Nginx deployment"
date: 2022-10-17T09:54:22+05:30
draft: false
---

Nginx is a web server that can also be used as a reverse proxy, load balancer, mail proxy and HTTP cache.  Nginx is free and open-source software.

##### ➡️ This deployment uses the official Nginx Docker image.

➡️ Go to create apps page and Search nginx on the search bar.

➡️ Click on install button. 

➡️ Fill all the reqired feilds.

| PRODUCT NAME  |
| :--------     | 
| `nginx`       |

`PROTOCOL`

| HTTP          | TCP/UDP       |
| :--------     | :--------     |
| `80,90`       | `3306,5432`   |

➡️ click on Advanced.

| ENV VARIABLE         |  WHITELIST                                                       |        WORKING DIR          |
| :---------           | :--------                                                        |:----------------------------| 
| `Give env variable`  | `If you want to white list any ports list here`                  |`WORKDIR for the application`|

➡️ Click on the Install button.

➡️ You will be redirected to My Apps page, Here you can find all the applications you deployed.

![App Screenshot](images/myapps.png)

➡️ Copy the nginx application Hostname without NodePort and search the Url. 

➡️ Now you can able to access the nginx webpage. 

![App Screenshot](images/nginx-page.jpg)
