# Web infrastructure design
- A lot of websites are powered by simple web infrastructure, a lot of time it is composed of a single server with a LAMP stack.

## 0. A simple web stack
- A whiteboard design: a one server web infrastructure that hosts the website that is reachable via www.foobar.com.

## 1. Distributed web infrastructure
- A whiteboard design: a three server web infrastructure that hosts the website www.foobar.com.

## 2. Secured and monitored web infrastructure
- A whiteboard design: a three server web infrastructure that hosts the website www.foobar.com, but secure, monitored and serves encrypted traffic.

## 3. Scale up
- A server, one load-balancer (HAproxy) configured as cluster with the other one, split components (web server, application server, database) with their own server.
