# IceBarPlus

> 一个基于 Manifest V3 构建的强大的 Microsoft Edge 浏览器安全测试工具

## 📁 项目结构

```
IceBarPlus/
├── config/             # 配置文件
│   ├── jest.config.js
│   ├── postcss.config.js
│   ├── tailwind.config.js
│   ├── tsconfig.json
│   └── vite.config.ts
├── dist/               # 构建产物（可直接加载的扩展）
│   ├── background/
│   ├── content/
│   ├── popup/
│   └── manifest.json
├── docs/               # 文档
│   ├── CHANGELOG.md
│   ├── DEVELOPMENT.md
│   ├── INSTALLATION.md
│   ├── README.md
│   └── USER_GUIDE.md
├── src/                # TypeScript 源代码
│   ├── background/     # 后台脚本
│   ├── components/     # React 组件
│   ├── content/        # 内容脚本
│   ├── hooks/          # 自定义 Hooks
│   ├── popup/          # 弹出窗口 UI
│   ├── types/          # TypeScript 类型定义
│   └── utils/          # 工具函数
├── dist.crx            # 已打包的扩展文件
├── dist.pem            # 签名密钥
└── package.json        # 依赖配置
```

## ✨ 核心功能

| 模块 | 功能 |
|------|------|
| 🔌 HTTP请求测试器 | 支持所有HTTP方法、自定义headers和body |
| 💉 SQL注入检测 | 自动漏洞扫描、多payload测试、自定义字典支持 |
| ⚡ XSS漏洞测试 | payload预设库、上下文感知测试 |
| 🔒 CSRF令牌分析 | 自动提取、安全性评估 |
| 🔄 请求重放 | 历史记录管理、一键重放 |
| 📋 响应头分析器 | 安全header检测 |
| 🔗 代理设置 | 快速切换Burp Suite/ZAP等代理工具 |

## 🚀 快速开始

```bash
# 安装依赖
npm install

# 开发模式
npm run dev

# 构建项目
npm run build

# 运行测试
npm test
```

## 📖 文档

- **安装指南**: `docs/INSTALLATION.md`
- **使用手册**: `docs/USER_GUIDE.md`
- **开发文档**: `docs/DEVELOPMENT.md`
- **更新日志**: `docs/CHANGELOG.md`

## 🔧 技术栈

- React 18 + TypeScript
- Vite 5 构建系统
- Tailwind CSS 3
- Manifest V3

## 📝 许可证

MIT License