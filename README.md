# nginx-module-libs
nginx module libs

## Usage

Download the dynamic module which you need, and put it in `/path/to/NGINX_CONFIGURE_PREFIX/modules`, then load it in the `nginx.conf` :

```conf

load_module modules/YOUR_MODULE.so;

```
