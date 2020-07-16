# asset

Some asset for develop

## add git user and email

```bash
git config --global user.name 'name'
git config --global user.email 'email'
```

## tar command

```bash
# .tar
tar -cvf archive-name.tar directory-to-compress
tar -xvf archive-name.tar -c directory-to-decompress

# .tar.gz
tar -zcvf archive-name.tar.gz directory-to-compress
tar -zxvf archive-name.tar.gz -c directory-to-decompress

# .tar.bz2
tar -jcvf archive-name.tar.bz2 directory-to-compress
tar -jxvf archive-name.tar.bz2 -c directory-to-decompress
```

## zip command

```bash
zip -r archive-name.zip directory-to-compress
unzip archive-name.zip -d direcotory-to-decompress
```

## 海豚畅游

github：https://github.com/ayooay/glbproxy

获取 chrome 插件

```bash
wget https://github.com/ayooay/glbproxy/releases/download/do2/Dolphin-chrome-3.3.0.crx
```

## Ubuntu

1. 截图软件：Shutter

## npm registry

淘宝 npm 镜像

```bash
# 设置淘宝镜像
npm config set registry https://registry.npm.taobao.org

# 配置后可通过下面方式来验证是否成功
npm config get registry
```
