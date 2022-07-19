<br>
<p align="center">
  <img src="https://assets.website-files.com/6105315644a26f77912a1ada/610540e8b4cd6969794fe673_Holberton_School_logo-04-04.svg" height="50%" width="40%"/>
</p>

<h2 align="center"> WEB INFRASTRUCTURE DESIGN</h2>
<br>


## Concepts
- DNS
- Monitoring
- Web Server
- Network basics
- Load balancer
- Server


## Learning Objectives
### General
- You must be able to draw a diagram covering the web stack you built with the sysadmin/devops track projects
- You must be able to explain what each component is doing
- You must be able to explain system redundancy
- Know all the mentioned acronyms: LAMP, SPOF, QPS

## 0. Simple web stack
### You must add:

- 1 server
- 1 web server (Nginx)
- 1 application server
- 1 application files (your code base)
- 1 database (MySQL)
- 1 domain name foobar.com configured with a www record that points to your server IP 8.8.8.8


## 1. Distributed web infrastructure
### You must add:

- 2 servers
- 1 web server (Nginx)
- 1 application server
- 1 load-balancer (HAproxy)
- 1 set of application files (your code base)
- 1 database (MySQL)


## 2. Secured and monitored web infrastructure
### You must add:

- 3 firewalls
- 1 SSL certificate to serve www.foobar.com over HTTPS
- 3 monitoring clients (data collector for Sumologic or other monitoring services)


## Author

- Piero Ramirez | [GitHub](https://github.com/Piero2023)
