
#ABOUT
这个项目只包含[bcloud](https://github.com/LiuLang/bcloud)的安装包,
以方便各位朋友使用.

#Debian系列
请直接下载bcloud-x.x.x.deb这个包, 安装时如果系统里面有gdebi的话, 只需要双击
deb包就能安装了; 如果没有的话, 也可以在终端里面安装:

    $ sudo dpkg -i bcloud-x.x.x.deb
    $ sudo apt-get -f update

ubuntu 12.04 的系统里没有python3-urllib3这个包, 请下载那个
python3-urllib3-1.3-3-all.deb, 先安装它, 再安装bcloud就可以了.

#Fedora系列
Fedora 20的话, 请直接下载并安装bcloud-x.x..fc20.noarch.rpm, 它会自动解决所有
依赖关系.

#OpenSuSE安装指南
**适用于12.3及以上版本, factory用户可以尝试. 其他用户请等待obs服务**

+ 请先安装提供的 `python3-keyring-x.y-r.suse.noarch.rpm` 以及 `python3-urllib3-x.y-r.suse.noarch.rpm`
+ 安装 `bcloud-x.y.z-r.suse.noarch.rpm`
+ 后续升级可以直接下载`bcloud-x.y.z-r.suse.noarch.rpm`
+ obs正在构建, 相信很快就能有软件源了
+ **KDE用户请阅读下面注意事项**:
    + 请更新您的系统之后再安装bcloud
    + 若经过第一步骤仍不能启动且终端输出gi相关错误可以尝试安装gtk3-devel
    + 美化Gtk3程序: 系统设置->应用程序外观->Gtk->选择一个GTK3主题: Zukitwo.
      若没有此主题可以在右下方"获取新主题"->"下载GTK3主题"中获得
#Archlinux安装
+请先从AUR上安装python-urllib3和python-keyring
