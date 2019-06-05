# template-ts-node-library
ts编写node库的基本模板

> 需要把ts写的编译成js，同时生成*.d.ts文件

- 在src目录下编写ts文件

- 将其编译到dist目录

  这一步记得在tsconfig.json中开启`"declaration": true`，这样编译时会生成*.d.ts文件

- 在package.json中指定 `"main": "./dist/index.js"`

  告知其他项目如何引入当前模块
