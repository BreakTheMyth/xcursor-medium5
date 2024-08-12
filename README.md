# 简介

此光标移植自[【五维介质自制鼠标指针】](https://www.bilibili.com/video/BV1q3411Z72c/?share_source=copy_web&vd_source=07889427324b59af06fa17a79c7a5378)，已经作者许可。

# 安装

```sh
sudo git clone https://github.com/BreakTheMyth/xcursor-medium5.git /usr/share/icons/xcursor-medium5/ && sudo cp /usr/share/icons/default/index.theme /usr/share/icons/default/index.theme.bak && sudo sed -i 's/^Inherits=.*/Inherits=xcursor-medium5/' /usr/share/default/index.theme && echo "finish"
```

# 卸载

```sh
sudo rm -rf /usr/share/icons/xcursor-medium5/ && sudo mv /usr/share/icons/default/index.theme.bak /usr/share/icons/default/index.theme && echo "finish"
```

