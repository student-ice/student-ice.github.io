# Deepin 20.6安装fcitx5

# [deepin官网](https://www.deepin.org) [deepin论坛](https://bbs.deepin.org)

#### 1.卸载系统自带的fcitx4

```
sudo apt purge fcitx* 卸载相关软件包

sudo apt autoremove 清理依赖包

rm -rf ~/.config/fcitx 删除配置文件目录
```

#### 2.安装fcitx5输入法

```
sudo apt update 更新源

sudo apt install fcitx5 fcitx5-chinese-addons 安装Fcitx5框架以及基于此框架的中文输入法
```

#### 3,注销重新登陆

ctrl+shift切换到fcitx5
