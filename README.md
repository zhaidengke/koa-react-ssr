# koa-react-ssr
react ssr 开发体验初步升级

├── dist // 生产环境打包后的资源存放目录
│ ├── static //打包的静态资源文件
│ | ├── index.js // 打包后的文件
│ ├── server //服务端文件目录
│ | ├── app.js //node server 启动入口
├── src // 源码目录
│ ├── client //前端代码
│ │ ├── app // 前端渲染入口
│ | ├── pages // 业务页面
│ │ | ├── index //默认首页
│ │ ├── router // 路由配置
│ │ ├── common // 存放通用组件和通用模块
│ ├── server // node 代码
│ │ ├── app // 服务入口 
│ │ ├── middlewares //中间件
│ │ | ├──  react-ssr.js //ssr 中间件
│ ├── share // 双端共享的代码可以放这里
├── webpack //构建配置
│ ├── scripts //构建脚本目录
│ │ | ├──  start.js //开发环境的所有服务启动入口
│ ├── webpack.dev.config.js //前端代码的开发环境编译配置
│ ├── webpack.server.config.js 服务端代码的编译配置


webpack-node-externals
chalk