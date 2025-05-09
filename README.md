![1746603003045](https://github.com/design-any/images/blob/main/designany/1746603003045.jpg)
![1746603054823](https://github.com/design-any/images/blob/main/designany/1746603054823.jpg)

#### 试用

http://njttac.ikuai5.com:63689/web/index.html

账号/密码:   123/123

#### 介绍

DesignAny 是一款低代码（lowcode）工具。其设计目标简化软件开发的流程，减少开发配置，调试，发布。让软件开发成为一个简单的事情。

DesignAny 使用拖拽和设计的方式来完成 H5 的网页应用开发、APP 应用开发、Restful Api 开发。

DesignAny 系统内置了一些基础组件，如果基础组件满足不了业务要求，也可以自己开发插件并导入，参考[extandComponents](https://github.com/design-any/extandComponents)。基础组件也会不定期升级更新，最终形成一个丰富的基础组件库。

DesignAny 目前没有完全开源的计划，但用户可以免费使用它。

此库是 DesignAny 应用程序的最终打包，用户可以直接部署它。

#### 软件架构

DesignAny 的前端使用 vue3+typescript 开发，后端使用 c#开发，基于.net core 3.1

#### 使用方法

1.下载当前库的指定版本到自己的服务器。

2.安装 dotnet-runtime-3.1.32-win-x64.exe

3.启动 Server 文件夹中的 LYLServer.exe，启动后占用 63013 端口，请保证该端口不被其它程序占用着。

4.在浏览器中打开http://127.0.0.1:63013/web/index.html。

#### 目前功能

| 功能         | 描述                                                                   |
| ------------ | ---------------------------------------------------------------------- |
| 支持平台     | Windows_x64。支持 linux 和 docker 的，但是没有打包也没有编写部署方案。 |
| 前端设计引擎 | 已完成，持续升级中                                                     |
| 工作流引擎   | 正在开发                                                               |
| 自定义插件   | 可自定义组件和页面                                                     |
