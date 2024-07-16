# wangEditor v5 doc

线上地址：https://cycleccc.github.io/docs/

## 本地开发

使用 [VuePress v2](https://v2.vuepress.vuejs.org/zh/) 搭建的文档。

全局安装 vuepress `npm install vuepress -g`

下载当前代码，然后启动

```shell
pnpm install     # 安装依赖
pnpm docs:dev # 启动，浏览器访问 http://localhost:8080/
```

## 发布上线

提交 main 分支代码，即可触发 [github actions](https://github.com/cycleccc/wangEditor-v6-doc/actions) 并发布上线。
