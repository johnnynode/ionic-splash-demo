### 关于ionic 启动页相关事项
- 安装安卓平台：$ `cordova platform add android` 初次初始化需要添加安卓平台
- 启动页图片路径：/resources/splash.png 最小尺寸：2208 * 2208
- 图标图片路径：/resources/icon.png 合适尺寸：1024 * 1024
- 自动裁剪: $ `ionic cordova resources android` 为安卓生成对应的图标和启动页 初次使用可能需要登陆后使用

### 关于启动页的相关设置,加载完成立即隐藏启动页
config.xml中的操作：
1. 添加
```xml
<preference name="AutoHideSplashScreen" value="false" /> 

```
2. 去除
```xml
<preference name="SplashScreenDelay" value="3000" />
```

在$ionicPlatform.ready事件中的处理:
```javascript
// 隐藏启动页
if (navigator.splashscreen) {
  navigator.splashscreen.hide();
}
    
```

### 相关博客学习参考
- http://blog.csdn.net/zapzqc/article/details/42237935
- http://blog.csdn.net/zapzqc/article/details/41802453
- http://blog.csdn.net/tyro_java/article/details/74606239

### 关于gradle
- https://services.gradle.org/distributions/

### 免责声明
- 图标和启动页使用淘宝相关图片，版权归淘宝所有，仅作学习使用

