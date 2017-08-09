# Ubuntu适应计划
1. 终端和在终端里打开的编辑器无法输入中文的问题：
```shell
gsettings set org.gnome.settings-daemon.plugins.xsettings overrides "{'Gtk/IMModule':<'fcitx'>}"
```
