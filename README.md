# Hello World Website

一个用 Node.js 内置 `http` 模块构建的 Hello World 网站，无需安装任何依赖。

## 运行

```bash
node server.js
# 或
npm start
```

浏览器打开 http://localhost:3000 即可看到页面。

## 项目结构

```
.
├── server.js            # Node.js HTTP 服务器（含路径穿越防护）
├── package.json         # 项目配置
└── public/
    └── index.html       # Hello World 页面
```

## 环境变量

| 变量 | 默认值 | 说明 |
|---|---|---|
| `HOST` | `0.0.0.0` | 监听地址 |
| `PORT` | `3000` | 监听端口 |
