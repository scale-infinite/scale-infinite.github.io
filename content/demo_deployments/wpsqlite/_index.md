---
title: "Wordpress Sqlite"
date: 2022-10-17T09:41:45+05:30
draft: false
---


SQLite is a opensource SQL database that stores data to a text file on a device. WordPress is a free and open-source content management system written in hypertext preprocessor language and paired with a MySQL or MariaDB database with supported HTTPS.

➡️ Go to create apps page and Search scaleinfinite/wpsqlite on the search bar.

➡️ Click on install button. 

➡️ Fill all the reqired feilds.

| PRODUCT NAME  |
| :--------     | 
| `Wpsqlite`    |

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

➡️ Copy the wpsqlite application Hostname without NodePort and search the Url. 

➡️ Change the port in the starting of Url to port 80 to access the application.

![App Screenshot](images/sqlitelink.png)

➡️ Now you can see the wordpress language selection page. 

![App Screenshot](images/wordpress-lang.png)

➡️ After selecting language you will be directly redirected to site creation page and fill all the fields like site name and username and so on.

![App Screenshot](images/wordpress-welcome.png)

➡️ Then Login with that detials.

![App Screenshot](images/wordpress-login.jpg)

➡️ Then you will be redirected to the wordpress Admin dashboard.

![App Screenshot](images/wordpress-dashboard.jpg)





