# kugou-vue-cordova

一个仿照酷狗的app,所使用的技术有：vuejs+vuex+vue-router+nodejs+cordova

### 使用方法

修改yourpath/kugou/proxy.js  端口和ip

修改yourpath/kugou/src/config/server.js  端口和ip

``` bash
cd kugou

# 安装依赖
npm install

# 在浏览器中预览 请使用chrome切换成手机模式
npm run dev

# 在手机预览 手机连接电脑usb 开启usb调试 连接电脑wifi
node proxy.js && npm run android
```
