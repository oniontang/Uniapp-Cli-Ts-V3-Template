<div align=center>
  
![vite](https://img.shields.io/badge/2.9.1-vite-orange)
![sass](https://img.shields.io/badge/1.49.9-sass-orange)
![vue](https://img.shields.io/badge/3.2.31-vue-brightgreen)

</div>

<div align=center>

![pinia](https://img.shields.io/badge/2.0.12-pinia-yellow)
![uni-ui](https://img.shields.io/badge/1.4.12-uni--ui-409EFF)
![typeScript](https://img.shields.io/badge/4.6.3-typeScript-lightgrey)
![vk-uview-ui](https://img.shields.io/badge/1.3.3-vk--uview--ui-blueviolet)

</div>

# ⚡️ 简介

一个开箱即用，基于 `vite 2` + `vue 3` + `uview-ui` + `pinia` + `uni-ui` 的`uniapp`项目模板。

# 🚀 开发

1. 安装

```
npm install
```

2. 运行

```
npm run serve
```

`运行成功后，使用微信开发者工具，选择mp-weixin目录并打开（路径：dist/dev/mp-weixin），即可预览。`


# 📦️ 多环境打包

- 测试环境打包

```
npm run build:test
```

- 生产环境打包

```
npm run build
```

`打包完成后，使用微信开发者工具，选择mp-weixin目录并打开，目录路径：dist/build/mp-weixin，在微信开发者工具中点击上传即可。`


# 🔧 代码检查修复

- 格式检查修复

```
npm run lint
```

# 📚 目录

```
├─ .env.xxx // 各环境的配置文件
├─ .eslintrc.js // eslint配置
├─ vite.config.ts // 项目配置
├─ tsconfig.json // ts配置
├─ index.html // 入口文件
└─ src
  │─ App.vue // 根容器
  │─ main.ts
  │  
  ├─ components // 组件
  │          
  ├─ config // 项目级配置
  │    │
  │    └─index.ts
  │      
  ├─ pages // 页面
  │                          
  ├─ router // 路由
  │          
  ├─ servers // 接口
  │   │  
  │   │─ request.ts // 封装
  │   └─ api // 接口
  │      
  ├─ static // 静态资源
  │              
  ├─ store // pinia             
  │      
  ├─ types // ts类型定义
  │      
  └─ utils // 工具库
  │ │  index.ts
  │ │  toast.ts // 弹窗封装
  └─
```
