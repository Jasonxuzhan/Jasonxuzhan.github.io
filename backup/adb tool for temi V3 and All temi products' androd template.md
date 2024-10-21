#adb工具下载后解压缩到指定位置，无需安装，使用方法如下：
## 让计算机连接机器人
1. 确保你的计算机和机器人连上了同一个Wi-Fi网络；
2. 在temi上打开设置 -> temi开发者选项 -> 点击打开ADB调试端口，注意temi的ip地址，并打开端口；
3. `在你的计算机上，利用上一步的IP地址，可以让计算机通过ADB连接到机器人并测试你的应用，在有ADB环境的终端下输入以下命令并按下回车：_adb connect IP_ADDRESS:5555_
4. 如果连接成功会显示 _connected to IP_ADDRESS:5555_
## 安装应用
按上述步骤成功连接机器人后，你可以在终端输入以下命令安装你的应用：
_adb install [option] PATH_OF_APK_
## 卸载应用
按上述步骤成功连接机器人后，你可以在终端输入以下命令卸载你的应用：
_adb uninstall [option] PACKAGE_NAME_
[更多ADB相关内容请参考]（https://developer.android.com/tools/adb?hl=zh-cn）
[adb工具.zip](https://github.com/user-attachments/files/17462041/adb.zip)
