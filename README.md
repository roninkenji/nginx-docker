# nginx-docker

NGINX server under Alpine Linux userspace

[NGINX Project Page](www.nginx.com)

## What is NGINX?
NGINX is a free, open-source, high-performance HTTP server and reverse proxy, as well as an IMAP/POP3 proxy server. NGINX is known for its high performance, stability, rich feature set, simple configuration, and low resource consumption.

NGINX is one of a handful of servers written to address the C10K problem. Unlike traditional servers, NGINX doesn't rely on threads to handle requests. Instead it uses a much more scalable event-driven (asynchronous) architecture. This architecture uses small, but more importantly, predictable amounts of memory under load. Even if you don't expect to handle thousands of simultaneous requests, you can still benefit from NGINX's high-performance and small memory footprint. NGINX scales in all directions: from the smallest VPS all the way up to large clusters of servers.

## Directions:

### Data Volumes:
 * /config : in this path NGINX will store it's configuration files.
 * /var/log/nginx : in this path NGINX will store it's configuration files.

### Network Ports:
 * 80 : Default webservice port
 * 443 : (Initially disabled) SSL webservice port

