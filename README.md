# Aria2一键完美配置魔改版 for Colab

小白自用学习魔改版，感谢源项目作者提供脚本。

源作者地址：

Aria2 一键安装管理脚本 增强版：https://github.com/P3TERX/aria2.sh

OneClickRun：https://github.com/biplobsd/OneClickRun

# 主要功能

调用源作者大佬一键安装Aria2和ngrok内网穿透脚本，优化安装过程，真一键全自动安装

使用源作者大佬Aria2完美配置方案

优化源作者大佬开启上传GD方法，自行添加相关配置链接后安装即实现下载完成全自动上传Google Drive，完成后删除本地文件

# 使用方法

下载笔记本到本地，上传到Colab，参照源作者的一键脚本教程配置以下文件：

Rclone Config：https://p3terx.com/archives/offline-download-of-onedrive-gdrive.html

Aria2 Config和Script Config：https://p3terx.com/archives/aria2-oneclick-installation-management-script.html

配置好上传到可直链下载的位置后（可以直接用GoIndex等目录直链永久使用）输入到笔记本对应位置，一键执行，看到Aria2简单配置信息和rpc config后点击链接，复制下方rpc config地址和端口到ariang修改即可！（小白能力有限，魔改版直接调用源Colab作者ngrok配置操作，可使用源作者的免费token也可以使用自己的token。token获取地址：https://dashboard.ngrok.com/auth
