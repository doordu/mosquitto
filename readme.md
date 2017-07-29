多度 Mosquitto
=================

## 说明

Mosquitto多度增强版本，增加上线下线状态，取消推送，超时等机制。

## 依赖

* c-ares (libc-ares-dev on Debian based systems) - disable with `make WITH_SRV=no`
* libuuid (uuid-dev) - disable with `make WITH_UUID=no`
* libwebsockets (libwebsockets-dev) - enable with `make WITH_WEBSOCKETS=yes`
* openssl (libssl-dev on Debian based systems) - disable with `make WITH_TLS=no`

## 安装

    make && make install
    

## 配置

**mosquitto.conf**
