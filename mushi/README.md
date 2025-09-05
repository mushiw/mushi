# Mushi Cydia Repository

这是一个Cydia插件仓库，包含Mushi插件。

## 添加仓库到Cydia

1. 打开Cydia应用
2. 点击"软件源"标签
3. 点击右上角的"编辑"按钮
4. 点击左上角的"添加"按钮
5. 输入仓库URL：`https://your-username.github.io/mushi/`
6. 点击"添加源"
7. 等待Cydia更新软件源列表

## 安装插件

1. 在Cydia中搜索"Mushi"
2. 点击插件名称
3. 点击右上角的"安装"按钮
4. 确认安装
5. 重启SpringBoard或设备

## 仓库结构

```
mushi/
├── debs/                                    # 插件包目录
│   └── com.mushi.mushi_1.0.0-8+debug_iphoneos-arm.deb
├── Packages                                 # 包信息文件
├── Release                                  # 仓库信息文件
└── README.md                               # 说明文档
```

## 注意事项

- 请确保您的设备已越狱
- 安装前请备份重要数据
- 如遇到问题，请检查设备兼容性