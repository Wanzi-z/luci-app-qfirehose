# LuCI QFirehose 应用

QFirehose的LuCI网页界面，为OpenWrt设备提供了一个用户友好的高通固件烧写工具。

## 功能特点

- 简单易用的固件烧写网页界面
- 自动USB设备检测
- 实时日志监控
- 支持多个USB端口和设备
- 固件烧写进度跟踪
- 自动完成检测

## 依赖包

本插件需要安装以下依赖包：
- luci-base
- qfirehose
- unzip
- kmod-usbmon
- debugfs
- luci-compat

## 安装方法

1. 将此仓库添加到您的OpenWrt构建系统中
2. 编译软件包：
```bash
make package/luci-app-qfirehose/compile V=s
```

3. 在您的OpenWrt设备上安装生成的软件包：
```bash
opkg install luci-app-qfirehose_1.0.0_all.ipk
```

## 使用方法

1. 访问OpenWrt的LuCI网页界面
2. 导航到 调制解调器 -> QFirehose
3. 选择固件文件
4. 选择适当的USB端口和设备
5. 点击"烧写"开始固件烧写过程
6. 通过日志窗口监控进度


https://github.com/user-attachments/assets/9247c8ed-72e0-4fe3-86cf-9d1cbbf443c7



## 许可证

本项目采用GPLv3许可证 - 详见LICENSE文件

## 作者

- Zag (ntbowen2001@gmail.com)
- 主页：https://pcat.qsim.top

## 贡献

欢迎提交贡献！请随时提交Pull Request。
