## Introduction
NGINX is open source software for web serving, reverse proxying, caching, load balancing, media streaming, and more. It started out as a web server designed for maximum performance and stability. In addition to its HTTP server capabilities, NGINX can also function as a proxy server for email (IMAP, POP3, and SMTP) and a reverse proxy and load balancer for HTTP, TCP, and UDP servers.

## Installation
```sudo apt-get update```
```sudo apt-get install nginx```

## Managing Nginx Process
To stop your web server, type:

```sudo systemctl stop nginx```

To start the web server when it is stopped, type:

```sudo systemctl start nginx```

To stop and then start the service again, type:

```sudo systemctl restart nginx```

If you are simply making configuration changes, Nginx can often reload without dropping connections. To do this, type:

```sudo systemctl reload nginx```
By default, Nginx is configured to start automatically when the server boots. If this is not what you want, you can disable this behavior by typing:

```sudo systemctl disable nginx```
To re-enable the service to start up at boot, you can type:

```sudo systemctl enable nginx```
