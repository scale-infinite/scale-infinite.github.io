---
title: "Linux VPS deployment"
date: 2022-10-17T09:50:04+05:30
draft: false
---

The linux vps is a virtual private server in contain that you can spinup in secconds ,connect and use. This is same as you personal computer.  

➡️ Go to create apps page and Search scaleinfinite/linuxvps on the search bar.

➡️ Click on install button. 

➡️ Fill all the reqired feilds.

| PRODUCT NAME  |
| :--------     | 
| `Linux VPS`     |

`PROTOCOL`

| HTTP          | TCP/UDP       |
| :--------     | :--------     |
| `80,90`       | `3306,5432`   |

➡️ click on next.

| PORT NUMBER   |
| :--------     |
| `default 22`  |

➡️ click on next.

| ENV VARIABLE         |  WHITELIST                                                       |        WORKING DIR          |
| :---------           | :--------                                                        |:----------------------------| 
| `Give env variable`  | `If you want to white list any ports list here` `Example` `82`   |`WORKDIR for the application`|

➡️ Click on the Finish button.

➡️ You will be redirected to My Apps page, Here you can find all the applications you deployed.

![App Screenshot](images/myapps.png)

➡️ Copy the Linuxvps application Hostname without NodePort and search the Url. 

➡️ Change the port in the starting of Url to port 80 to access the application.

➡️ Now you can see a similar window like this. 

![App Screenshot](images/vps-desktop.png)

➡️ From pressing the LADE symbol button you can access to terminal and file-system etc..,

![App Screenshot](images/terminal.png)






