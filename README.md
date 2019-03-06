## Web端直接播放.ts 格式视频

使用 [video.js](https://github.com/videojs/video.js) 开发团队的视频流格式转换工具库 [mux.js](https://github.com/videojs/mux.js) , 实现Web端直接播放 .ts 视频资源。此demo只作为可播放示例。

## 安装与运行
示例中使用原生AJAX获取同目录下示例ts文件， 如果要观看结果，请安装安装 `http-server` 起一个简易的本地服务。
```bash
npm install
```
运行：
```bash
npm run server
```
服务建立后即可打开浏览器输入 `localhost:8081` 查看视频播放
