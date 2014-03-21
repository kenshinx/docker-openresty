docker-openresty
================

Dockerfile build for openresty

* centos 
* openresty 1.4.3.6
* luajit 2.0

Use this image

```
docker pull  kenshinx/docker-openresty
```

Or

```
git clone git://github.com/kenshinx/docker-openresty.git
cd docker-openresty
docker build -t kenshinx/openresty:luajit .
```