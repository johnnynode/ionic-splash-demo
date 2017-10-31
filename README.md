Ionic App Base
==============

A starting project for Ionic that optionally supports using custom SCSS.

## Using this project

We recommend using the [Ionic CLI](https://github.com/ionic-team/ionic-cli) to create new Ionic projects that are based on this project but use a ready-made starter template.

For example, to start a new Ionic project with the default tabs interface, make sure the `ionic` utility is installed:

```bash
$ npm install -g ionic cordova
```

Then run:

```bash
$ ionic start myProject tabs --type=ionic1
```

More info on this can be found on the Ionic [Getting Started](https://ionicframework.com/getting-started) page and the [Ionic CLI](https://github.com/ionic-team/ionic-cli) repo.

## Issues

Issues have been disabled on this repo. If you do find an issue or have a question, consider posting it on the [Ionic Forum](https://forum.ionicframework.com/). If there is truly an error, follow our guidelines for [submitting an issue](https://ionicframework.com/submit-issue/) to the main Ionic repository.

### 关于ionic 启动页相关事项
- 安装安卓平台：$ `cordova platform add android` 初次初始化需要添加安卓平台
- 启动页图片路径：/resources/splash.png 最小尺寸：2208 * 2208
- 图标图片路径：/resources/icon.png 合适尺寸：1024 * 1024
- 自动裁剪: $ `ionic cordova resources android` 为安卓生成对应的图标和启动页 初次使用可能需要登陆后使用

### 免责声明
- 图标和启动页使用淘宝相关图片，版权归淘宝所有，仅作学习使用

