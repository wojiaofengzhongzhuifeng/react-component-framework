## 用途

## 功能

- 指定根文件, 并且添加脚本执行该根文件

- 使用相应的加载器将 typescript 打包成 JavaScript 代码

- 使用 webpack 进行打包

- 实现热更新(使用`yarn start`开启服务, 并且在 `/src/index.ts` 修改代码后, 页面自动更新), 使用 webpack-dev-serve(编译 js, 开启http服务) + html-webpack-plugin(生成根 index.html)

- 添加 react 框架, 完成第一个 button 组件

- 区分开发环境与生产环境, 主要是生产环境排除 react 库