<div align="center"><h1>
Python 工具箱 - Awespykit
</h1></div>

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/hrpzcf/AwesomePyKit?label=Stars&logo=github)](https://github.com/hrpzcf/AwesomePyKit/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/hrpzcf/AwesomePyKit?label=Forks&logo=github)](https://github.com/hrpzcf/AwesomePyKit/network)
[![GitHub issues](https://img.shields.io/github/issues/hrpzcf/AwesomePyKit?label=Issues&logo=github)](https://github.com/hrpzcf/AwesomePyKit/issues)
[![GitHub license](https://img.shields.io/github/license/hrpzcf/AwesomePyKit?color=red&label=License)](https://github.com/hrpzcf/AwesomePyKit/blob/main/LICENSE)
[![GitHub license](https://img.shields.io/github/v/release/hrpzcf/AwesomePyKit?label=Release&logo=github)](https://github.com/hrpzcf/AwesomePyKit/releases)

</div>

## 快速跳转

[程序概述](#程序概述) / [如何运行](#如何运行) / [程序截图](#程序截图) / [源码仓库](#源码仓库)

<br />

## 程序概述

`仅支持在windows系统上运行`

这是一个关于 Python 的工具箱，提供包管理器、程序打包工具、镜像源设置工具、模块安装包下载器。

界面简陋，但不影响使用。

<br />

## 如何运行

> 从 exe 可执行文件运行：

1. 打开 Awespykit 版本发布页 [GitHub](https://github.com/hrpzcf/AwesomePyKit/releases) / [Gitee](https://gitee.com/hrpzcf/AwesomePyKit/releases)
2. 下载打包好的程序包 Awespykit-x.x.x.7z
3. 将压缩包解压，找到 runpykit.exe 双击运行

<br />

> 从源代码运行：

1. 本机安装 Python 3.7 或更新版本的 Python 运行环境
2. `git clone` 克隆源代码或下载源代码包 Source code.zip 解压
3. 在 Awespykit 目录内打开 PowerShell 或 Cmd
4. 安装 Awespykit 的依赖，有多个 Python 环境的请自行选择环境

    ```cmd
    python -m pip install -r requirements.txt
    ```

5. 找到 runpykit.py 运行。如果不想显示控制台，可以将 runpykit.py 重命名为 runpykit.pyw
6. *注意*：由于更改了项目目录结构，使用 Pycharm 的同学，Pycharm 打开 Awespykit 目录后，请右键 source 目录，选择菜单末尾的`将目录标记为->源代码根目录`，否则影响编程体验。

<br />

## 程序截图

> ### 包管理器：封装了 pip 命令

- 提供多 Python 环境的包管理，免于用命令行管理的混乱
    + 支持常规 Python 环境
    + 支持 venv 虚拟环境
    + 支持 Anaconda 主环境、虚拟环境
- 支持批量安装模块、按版本号安装等
- 支持检查更新、批量卸载、批量升级(不了解各包的互相依赖则请慎用批量功能)

![包管理器](./images/PackageManager.png)

<br/>

> ### 程序打包工具：封装了 Pyinstaller

- 封装了 Pyinstaller 的大部分常用命令
- 支持选择不同的环境进行打包操作
- 支持一键在项目下创建 venv 虚拟环境
- 支持项目所使用的 Python 环境的检查，检查出未安装的模块可一键安装

![程序打包工具](./images/PyinstallerTool.png)

<br/>

> ### 镜像源设置工具：封装了 pip 命令

- 使用 pip 时网络不佳，用此工具一键切换 pip 所使用的镜像源
- 支持保存你自己常用的镜像源地址

![镜像源设置工具](./images/IndexUrlTool.png)

<br/>

> ### 模块安装包下载器：封装了 pip 命令

- 用于特殊需求时下载各个包/库/模块的安装包
- 支持同时下载要下载的包/库/模块的依赖
- 支持从 requirement.txt 批量读取并一键下载

![模块安装包下载器](./images/PackageDownloader.png)

<br/>

## 源码仓库

> [Gitee](https://gitee.com/hrpzcf/AwesomePyKit) / [GitHub](https://github.com/hrpzcf/AwesomePyKit)
