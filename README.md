# MC 联机启动器（mc-room-launcher）

和好友一起开房联机用的 Minecraft 桌面启动器（中文界面）。

## 下载（见右侧 Releases）

- 安装版 `mcroom-setup-x.y.z.exe`：点开就装，开始菜单出图标，之后可自动更新
- 免安装版 `mcroom-portable-x.y.z.zip`：解压即用，不写注册表

启动器会自动检查最新版本并提示更新（更新包 sha256 校验通过才会替换）。

## 校验下载是否完整

在下载目录打开 PowerShell 或 CMD：

```
certutil -hashfile mcroom-setup-2.4.2.exe SHA256
```

输出与 `SHA256SUMS.txt` 中该文件一行一致，才可运行；不一致就删掉重下。