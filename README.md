# acme pack installer

ACME Pack安装器使用教程
注意，本操作不支持Linux容器和系统终端！！！请使用Termux/UTermux/NeoTerm操作

安装

```
apt install -y curl
bash -c "$(curl -LfsS 'https://gitee.com/SunWuKong443/acme-pack-installer/raw/master/i')"
```

卸载

```
apt install -y curl
bash -c "$(curl -LfsS 'https://gitee.com/SunWuKong443/acme-pack-installer/raw/master/u')"
```
仓库里的install有很多功能，但是需要克隆此仓库，此脚本为测试阶段，有bug请反馈
使用教程:

克隆

```
git clone https://gitee.com/SunWuKong443/acme-pack-installer.git
```
然后执行cd acme-pack-installer
使用教程:
先执行这个指令:`sh ./install -wd`

使用默认目录:`sh ./install -g`

安装到其他目录: `sh ./install -d 路径`

卸载: `sh ./install -u`

显示版本: `sh ./install -version`

帮助:`sh ./install -help`

压缩为mcpack到游戏目录:`sh ./install -gma`

压缩为zip到游戏目录:`sh ./install -gza`

压缩为mcpack到自定义目录:`sh ./install -ma 路径`

压缩为zip到自定义目录:`sh ./install -za 路径`

材质包下载地址:

[清玖云盘](https://cloud.qingstore.cn/#/s/ag8Xta)

#### 码云特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  码云官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解码云上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是码云最有价值开源项目，是码云综合评定出的优秀开源项目
5.  码云官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  码云封面人物是一档用来展示码云会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
