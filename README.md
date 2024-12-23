# How to Install LEMP on CentOS Stream 9

LEMP is a software stack used for web development. The acronym LEMP stands for:
- Linux – the operating system on which the stack is based.
- Nginx (pronounced Engine-X) – the web server, which serves web pages to users.
- MariaDB (or MySQL) – the database management system used to store and retrieve data.
- PHP (or sometimes Python/Perl) – the programming language used to process dynamic content and generate web pages.

The LEMP stack is popular because it offers a flexible, open-source solution for developing and deploying websites and web applications. Nginx, in particular, is known for its efficiency in handling high traffic loads and its ability to act as both a web server and a reverse proxy.

In this article, we will look at how to install LEMP on CentOS Stream 9.

## How to Install LEMP on CentOS Stream 9

In our example, the LEMP stack will consist of Linux, Nginx, MariaDB, and PHP.

## Install Nginx

Before installing any software, it’s good practice to ensure the system packages are up-to-date:
```
sudo dnf update
```
Install Nginx:
```
sudo dnf install nginx
```
Enable and start Nginx:
```
sudo systemctl enable --now nginx
```
Check the status of the Nginx service:
```
systemctl status nginx
```

![](images/nginx-status.png)

Continued on the [iolloi.icu](https://iolloi.icu/index.php/2024/11/19/how-to-install-lemp-on-centos-stream-9/)
