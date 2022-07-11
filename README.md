# install

依次安装三个组件, 其中 AppMarket 可以精简, 将 AppMarket.exe 删除可以避免启动主商店程序, 甚至可以只保留 aowgameex2.dat 文件.

然后导入两个注册表文件, 一个有镜像组件和 AppMarket 的安装路径, 一个有 adb 调试和手机像素等参数.

最后使用批处理脚本启动模拟器, 参数 `-vm "100"` 代表启动 `AOW_Rootfs_100` 镜像, 修改该数字和注册表可以多开.

