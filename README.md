## 硬件配置
* CPU: Intel® Pentium® Processor G4560
* 主板：微星 B150M-ICAFE
    * 声卡： Realtek® ALC887 译码芯片
    * 网卡：Realtek RTL8111H Gigabit LAN 控制器
* 显卡：富彩（forsa）GEFORCE GTX 1050

## 使用到的工具
* balenaEtcher
* Kext Utility
* u盘（大于8G）

## 安装说明
1. 下载 macOS High Sierra 镜像
2. 使用`balenaEtcher`将系统镜像烧录到U盘中
3. 挂载U盘的`EFI`分区，复制当前项目的`EFI`目录到该分区
4. 打开`Kext Utility`，将`Other/aDummyHDA.kext`这个文件拖入软件框内
5. 重启并安装系统