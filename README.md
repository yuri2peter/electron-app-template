# electron-app-template

一个 electron 程序的模板。

## 懒人包

你可以从该项目的[release](https://github.com/yuri2peter/electron-app-template/releases)中下载到带完整环境的模板，替换为自己的 app 源码后即可投入使用。

- [懒人包 1.0.0](https://github.com/yuri2peter/electron-app-template/releases/tag/1.0.0)
  > “懒”才是推进科技进步的第一生产力。

## 为什么需要它？

Electron 的打包比较繁琐，还可能碰到网络问题打包失败。该项目提供了一个已打包好的程序模板（懒人包），适用于简单的 NodeJS HTTP 服务器，也可以基于此项目作二次开发。

## 软件要求

- win64 操作系统

## 目录结构

```bash
|- electron-app-template # 根目录
  |- locales # 语言文件
  |- resources # 资源目录
    |- app # 应用目录
      |- dist # 服务目录
        |- main.js # 服务入口文件
      |- app.js # electron入口文件
    |- app.exe # 启动应用
```

Electron 入口文件默认设置启动 URL 为 `localhost:3000`，可以按需修改。

## 其他

- 如何打包一个零依赖的服务端代码？请参考[yuri2peter/web-aircraft-carrier](https://github.com/yuri2peter/web-aircraft-carrier)的服务端部分。
- 如果您想学习如何完整地构建一个 electron 应用，可以参考[electron/electron-quick-start](https://github.com/electron/electron-quick-start)。
