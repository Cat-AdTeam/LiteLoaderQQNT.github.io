# 安装

## 下载项目

[项目下载地址](https://github.com/LiteLoaderQQNT/LiteLoaderQQNT/releases/latest)

将下载到的 `LiteLoaderQQNT.zip` 文件解压到任意位置 (比如你存放软件/工具的文件夹) 并记住该路径稍后会用到。

## 根据系统选择安装方式

<details> <summary>windows</summary>

### 修补 QQ.exe

由于 Windows 上的 QQNT 添加了校验，需要执行以下步骤来避免程序闪退：

1. 右击 QQ 图标，选择 `打开文件位置` 以找到安装目录，复制当前路径，暂时不要关闭该文件夹。

2. 根据 QQ 版本选择 Patch 程序。32 位版本使用 `QQNTPatcher_x86.exe`，64 位版本使用 `QQNTPatcher_x64.exe`。

> 如何确定 QQ 版本：查看打开的安装路径，如果其中包含 `Program Files (x86)` 则为 32 位，没有则是 64 位

3. 打开 `QQNTPatcher_*.exe` 程序会弹出文件选择框，粘贴 QQ 的安装路径并选择该目录下的 QQ.exe 文件。等待终端显示 `Patched!` 后关闭窗口。
</details>

#### 插入加载器代码

1. 打开 QQ 安装目录，依次进入 `resources > app > app_launcher`。

2. 用记事本或其他文本编辑器打开 `index.js`。

3. 在文件顶部插入 `require("LiteLoaderQQNT 目录位置");` 将其中的 `LiteLoaderQQNT 目录位置` 替换为 `LiteLoaderQQNT` 文件夹路径，保存该文件。

4. 重新启动 QQ 即可在设置界面看到 LiteLoaderQQNT 设置选项，安装完成，玩的开心！