# @esign-ai/esign-cli

e签宝命令行工具。在命令行中访问 e签宝发起签署、合同管理、审批管理等平台能力

## npm 安装

```bash
npm install -g @esign-ai/esign-cli
esign --version
``+

- 需要 Node.js >= 14
- 安装时自动下载当前操作系统和架构对应的二进制
- 安装完成后提供 `esign` / `esign-cli` 命令

### 快速开始

```bash
# 查看帮助
esign --help

# 登录生产环境
esign auth login

# 登录沙箱环境
esign auth login --sandbox

# 不自动打开浏览器，输出授权链接
esign auth login --no-browser

# 查看认证状态
esign auth status

# 登出当前环境
esign auth logout
```

## 支持的平台

| 系统 | 架构 |
|---|---|
| Linux | amd64、arm64 |
| macOS | amd64、arm64 |
| Windows | amd64、arm64 |

## 版本管理

npm 包版本与 CLI 二进制版本保持一致。

```bash
# 更新到最新版本
npm update -g @esign-ai/esign-cli

# 安装指定版本
npm install -g @esign-ai/esign-cli@<version>

# 查看当前版本
esign --version

# 卸载
npm uninstall -g @esign-ai/esign-cli
```

