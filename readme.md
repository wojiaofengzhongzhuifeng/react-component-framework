## 用途

## 功能

- 指定根文件, 并且添加脚本执行该根文件

- 使用相应的加载器将 typescript 打包成 JavaScript 代码

- 使用 webpack 进行打包

- 实现热更新(使用`yarn start`开启服务, 并且在 `/src/index.ts` 修改代码后, 页面自动更新), 使用 webpack-dev-serve(编译 js, 开启http服务) + html-webpack-plugin(生成根 index.html)

- 添加 react 框架, 完成第一个 button 组件

- 区分开发环境与生产环境, 主要是生产环境排除 react 库

- 使用 jest 运行第一个单元测试(被测试文件支持 ts 语法)

- 将自己写的组件导出, 目的是别人通过 npm 下载包之后, 可以使用我们写好的组件(未实现自动化 npm publish)

- 使用 css-loader 加载 css 样式