---
title: "Grafana deployment"
date: 2022-10-17T09:58:22+05:30
draft: false
---

Grafana is a multi-platform open source analytics and interactive visualization web application. It provides charts, graphs, and alerts for the web when connected to supported data sources.

##### ➡️ This deployment uses the official Grafana Docker image.  

➡️ Go to create apps page and Search grafana on the search bar.

➡️ Click on install button.

➡️ Fill all the reqired feilds.

| PRODUCT NAME  |
| :--------     | 
| `grafana`    |

`PROTOCOL`

| HTTP          | TCP/UDP       |
| :--------     | :--------     |
| `3000`     |               |

➡️ click on Advanced.

| ENV VARIABLE         |  WHITELIST                                                       |        WORKING DIR          |
| :---------           | :--------                                                        |:----------------------------| 
| `Give env variable`  | `If you want to white list any ports list here`                  |`WORKDIR for the application`|

➡️ Click on the Install button.

➡️ You will be redirected to My Apps page, Here you can find all the applications you deployed.

![App Screenshot](images/myapps.png)

➡️ Copy the grafana application Hostname without NodePort and search the Url. 

➡️ Now you will access the application. And you need to login to grafana.

![App Screenshot](images/grafana-login.png)

➡️ Default Username and Password for grafana is admin.

➡️ After you will be required to add datasources and create dashboards to visualize your data.

`ADD DATASOURCE`

![App Screenshot](images/datasources.png)

➡️ Now you can create the dashboard and select the data source to visualize the data you need.

![App Screenshot](images/grafana-dashboard.png)

