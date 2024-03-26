## 项目使用重点说明
pnpm electron vite vue3使用pnpm暂时报错了
```
// 先直接使用npm 
node -v   20.11.0
npm -v 10.2.4

// 安装项目依赖
npm i 

// 本地运行项目
npm run start
```
## 数据存储使用sqlite3
```
// 暂时将数据库存放在command目录下了database.sqlite3 相当于本地记录所有的数据
```

## 可参考项目
  - https://github.com/caoxiemeihao/electron-vite-samples
  - https://github.com/1111mp/electron_client
  - https://github.com/fanchenio/DawnLauncher
## 参考文档
- https://www.electronjs.org/zh/docs/latest/tutorial/quick-start

## 初始化项目
- https://electron-vite.github.io/guide/getting-started.html

  pnpm i 安装依赖
  pnpm start 本地运行项目
  pnpm build 编译打包项目

## 中文乱码问题
chcp 65001

## 主进程和渲染进程间的通信
- https://www.cnblogs.com/badaoliumangqizhi/p/13040619.html

## 先安装两个工具
```
// 先设置成全局环境变量，方便通过名字直接调用
https://github.com/TheAlgorithms/Python
https://github.com/yt-dlp/yt-dlp
https://www.ffmpeg.org/download.html

// yt-dlp运行环境是需要安装python
yt-dlp --version
ffmpeg -version
```

## Menu菜单的设置
```
https://www.electronjs.org/zh/docs/latest/api/menu
```

## 引入node原生模块
```
https://www.electronjs.org/zh/docs/latest/tutorial/using-native-node-modules
```

## Electron 获取当前用户data存放目录
- https://segmentfault.com/a/1190000044417762

## npm build 报错 node-gyp

- https://github.com/caoxiemeihao/electron-vite-samples/issues/9
- https://www.cnblogs.com/RaySirBlog/p/17337079.html


## sqlite3 操作数据库api
- https://github.com/TryGhost/node-sqlite3/wiki/API

## python 打包成exe
- https://github.com/brentvollebregt/auto-py-to-exe


## ffmpeg
```
// 提取视频中的音频文件
ffmpeg -i input.mp4 -vn -c:a copy output.aac
```

## electron-build 打包添加静态资源
- https://www.cnblogs.com/mrwh/p/12961446.html?ivk_sa=1024320u