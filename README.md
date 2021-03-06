<img src="build/icons/128x128.png" alt="logo" height="80" align="right" />

# Electron Xiami

[English README](README.en.md)

Linux和macOS下的虾米客户端 (虾米播放器)，使用[Electron](https://electron.atom.io)构建。

![screenshot_macos](https://user-images.githubusercontent.com/13460738/34644583-38a2a2b6-f39e-11e7-8831-e21475427ccb.jpg)

![screenshot_gnome](https://user-images.githubusercontent.com/13460738/34747515-6fd6805c-f5fd-11e7-9aed-25f51c2e3b49.jpg)

![mini_mode](https://user-images.githubusercontent.com/13460738/35371056-af3971be-01f6-11e8-8a57-8a8c4b728432.png)

*请注意：这个项目不是虾米音乐的官方客户端。如果有任何问题请反馈到[这个链接](https://github.com/eNkru/electron-xiami/issues)。*

## 功能
* 虾米音乐在线
* 迷你播放模式
* 桌面歌词 （测试）
* 最小化到托盘
* 系统提示
* 播放控制
* 用户配置
* 多语言支持

## 安装需求
* [GIT](https://git-scm.com/)
* [NPM](https://www.npmjs.com/)

## 编译和安装
本地编译运行
```
git clone https://github.com/eNkru/electron-xiami.git
cd electron-xiami
npm install
npm start
```
编译打包版本
```
npm run dist:linux
```

## 发布
```
npm version (new release version)
git push origin master
git push origin --tags
npm publish
```

## 下载
预打包版本请点击[这个链接](https://github.com/eNkru/electron-xiami/releases)下载。

## 授权协议
[MIT](https://github.com/eNkru/electron-xiami/blob/master/LICENSE)
