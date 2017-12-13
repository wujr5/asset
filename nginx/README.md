# nginx 配置

> 2017 年 12 月 12 日

* 创建源码存放区域

```bash
mkdir ~/Desktop/nginx
```

* 下载 nginx 源码

```bash
wget http://nginx.org/download/nginx-1.13.7.tar.gz
tar -zxvf nginx-1.13.7.tar.gz
```

* 下载需要的模块

```bash
cd ~/Desktop/nginx
git clone https://github.com/yaoweibin/nginx_upstream_check_module.git
git clone https://github.com/simpl/ngx_devel_kit/archive/v0.3.0.tar.gz
```
