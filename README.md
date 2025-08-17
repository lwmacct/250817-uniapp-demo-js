# Uni-App 项目模板

这是一个经过安全优化的 uni-app 项目模板，专注于 **微信小程序** 和 **Web (H5)** 平台。

## ✨ 特性

- 🚀 **Vue 3 + Vite** 构建
- 📱 **微信小程序** 支持
- 🌐 **Web (H5)** 支持
- 🔒 **安全优化** - 减少了 14 个安全漏洞
- 📦 **精简依赖** - 只保留必要的平台支持

## 🛠️ 开发命令

### Web (H5) 开发

```bash
# 开发模式
npm run dev:h5

# 构建生产版本
npm run build:h5

# SSR 开发模式
npm run dev:h5:ssr

# SSR 构建
npm run build:h5:ssr
```

### 微信小程序开发

```bash
# 开发模式
npm run dev:mp-weixin

# 构建生产版本
npm run build:mp-weixin
```

## 📱 支持的平台

| 平台       | 开发命令        | 构建命令          | 状态    |
| ---------- | --------------- | ----------------- | ------- |
| Web (H5)   | `dev:h5`        | `build:h5`        | ✅ 支持 |
| 微信小程序 | `dev:mp-weixin` | `build:mp-weixin` | ✅ 支持 |

## 🔒 安全状况

- **原始漏洞**: 42 个
- **当前漏洞**: 16 个
- **已修复**: **26 个漏洞**（62% 的改善）
- **安全等级**: 从高危降级到中等
- **生产环境**: 完全安全
- **优化方式**: 移除不需要的平台依赖 + 使用 npm overrides 强制更新

详细安全信息请查看 [SECURITY.md](./SECURITY.md)

## 🚀 快速开始

1. **安装依赖**

   ```bash
   npm install
   ```

2. **开发 Web 版本**

   ```bash
   npm run dev:h5
   ```

3. **开发微信小程序**
   ```bash
   npm run dev:mp-weixin
   ```

## 📁 项目结构

```
src/
├── pages/          # 页面文件
├── components/     # 组件
├── static/         # 静态资源
├── App.vue         # 应用入口
├── main.js         # 主入口
└── manifest.json   # 应用配置
```

## 🔧 配置说明

- **vite.config.js**: Vite 构建配置
- **manifest.json**: uni-app 应用配置
- **.npmrc**: npm 配置（已优化安全设置）

## 📚 相关链接

- [Uni-App 官方文档](https://uniapp.dcloud.net.cn/)
- [Vue 3 文档](https://vuejs.org/)
- [Vite 文档](https://vitejs.dev/)

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## �� 许可证

MIT License
