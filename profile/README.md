# BeCrafter - 开发者工具生态

<p align="center">
  <img src="https://img.shields.io/github/stars/BeCrafter?style=flat-square" alt="Stars">
  <img src="https://img.shields.io/github/forks/BeCrafter?style=flat-square" alt="Forks">
  <img src="https://img.shields.io/github/license/BeCrafter?style=flat-square" alt="License">
</p>

👋 专注于打造 **轻量、实用、可复用** 的开发者工具套件，覆盖 AI 提示词管理、分布式系统、数据处理等核心场景。

---

## 🎯 项目总览

| 分类 | 项目数 | 代表作 |
|------|--------|--------|
| 🤖 AI 提示词生态 | 3 | prompt-manager, PromptCraft |
| 🔗 MCP 生态 | 2 | onemcp, iskill |
| ⚡ 分布式与系统 | 2 | go-ratelimiter |
| 📊 数据处理 | 2 | json2image, go-parser |
| 🛠️ 工具集封装 | 1 | commander |
| 🔬 实验性 | 1 | plugo |

---

## 🤖 AI 提示词生态

| 项目 | 描述 | 技术栈 | 状态 |
|------|------|--------|------|
| [prompt-manager](https://github.com/BeCrafter/prompt-manager) ⭐13 | MCP 协议 Prompt 管理服务，支持流式传输 + 双端管理 | JavaScript | ✅ 稳定迭代 |
| [PromptCraft](https://github.com/BeCrafter/PromptCraft) ⭐13 | 高质量 AI 提示词库展示平台 | TypeScript | 🚀 持续更新 |
| [prompt-mcp](https://github.com/BeCrafter/prompt-mcp) ⭐2 | MCP 协议兼容服务器，支持本地 / 远程对接 | JavaScript | ✅ 生产可用 |

---

## 🔗 MCP 生态 (Model Context Protocol)

| 项目 | 描述 | 技术栈 | 状态 |
|------|------|--------|------|
| [onemcp](https://github.com/BeCrafter/onemcp) | 智能 MCP 路由系统 - 统一管理多个 MCP 服务器 | TypeScript | ✅ 稳定迭代 |
| [iskill](https://github.com/BeCrafter/iskill) | 灵活的 Skill 安装管理工具，支持自定义路径 | TypeScript | ✅ 稳定迭代 |

### onemcp 核心特性

- 🔄 **服务聚合** - 将多个独立的 MCP 服务器统一到单一接口
- 🏷️ **工具命名空间** - 通过 `{serviceName}__{toolName}` 格式避免工具名称冲突
- 🔌 **连接池管理** - 优化资源使用，通过连接复用提高性能
- 🚀 **灵活部署** - 支持 CLI (stdio) 和 Server (HTTP) 两种模式
- 🌐 **多协议支持** - 支持 stdio、SSE 和 Streamable HTTP 三种传输协议
- 💚 **健康监控** - 自动检测服务健康状态，实现工具的自动加载/卸载
- 🎨 **交互式 TUI** - 提供友好的终端界面进行配置管理

### iskill 核心特性

- 📦 **多源格式支持** - GitHub 简写、URL、Git 仓库、本地路径
- 🔗 **符号链接安装** - 推荐方式，节省空间易更新
- 📋 **配置管理** - 支持项目级和全局配置文件
- 🔍 **智能搜索** - 交互式搜索和关键词匹配

---

## ⚡ 分布式与系统工具

| 项目 | 描述 | 技术栈 | 状态 |
|------|------|--------|------|
| [go-ratelimiter](https://github.com/BeCrafter/go-ratelimiter) ⭐10 | 4 种限流机制（固定窗口 / 滑动窗口 / 漏桶 / 令牌桶） | Go + Redis + Lua | ✅ 生产可用 |
| [sync-hub](https://github.com/BeCrafter/sync-hub) | 一源多目标文件同步，智能降级 | JavaScript | ✅ 稳定迭代 |

### go-ratelimiter 核心特性

- 🪣 **漏桶限流** - 平滑处理突发请求
- 🎫 **令牌桶限流** - 支持突发流量
- 📊 **滑动窗口** - 精确限流控制
- 🔢 **固定窗口** - 简单高效的计数限流

---

## 📊 数据处理工具

| 项目 | 描述 | 技术栈 | 状态 |
|------|------|--------|------|
| [json2image](https://github.com/BeCrafter/json2image) ⭐2 | JSON 数据可视化，规则化图片生成 | Go | ✅ 稳定迭代 |
| [go-parser](https://github.com/BeCrafter/go-parser) ⭐2 | 轻量级规则引擎，基于 Golang 语法解析 | Go | ✅ 生产可用 |

---

## 🛠️ 工具集封装

| 项目 | 描述 | 技术栈 | 状态 |
|------|------|--------|------|
| [commander](https://github.com/BeCrafter/commander) | 命令行多工具封装，集中管理分散工具 | Go + CLI | ✅ 稳定迭代 |

---

## 🔬 实验性项目

| 项目 | 描述 | 技术栈 | 状态 |
|------|------|--------|------|
| [plugo](https://github.com/BeCrafter/plugo) | Go 语言的插件系统，支持 TCP/Unix 通信 | Go | 🚧 开发中 |

---

## 📋 技术栈全景

### 核心技术栈

| 领域 | 技术 |
|------|------|
| **后端核心** | Go |
| **前端 / 工具链** | TypeScript, JavaScript |
| **缓存 / 分布式** | Redis |
| **脚本引擎** | Lua |
| **AI 协议** | MCP (Model Context Protocol) |

### 开发规范

- 🎨 RESTful API 设计
- 🧪 TDD 测试驱动
- 📌 语义化版本控制
- 📄 MIT License（全项目开源，商用友好）

---

## 🤝 贡献指南

### 贡献步骤

1. **Fork 仓库** → 创建特性分支（`git checkout -b feature/xxx` 或 `fix/xxx`）
2. 遵循项目代码规范，编写注释完善的代码
3. 运行测试用例（`go test` / `npm test`），确保无报错
4. 提交 PR 时，填写清晰的功能描述与修改说明
5. 参与代码评审，根据反馈迭代优化

### 贡献者公约

- 尊重他人代码，保持友好沟通
- 不提交无意义的修改（如格式调整、拼写错误单独 PR）
- 新功能需同步更新文档与测试用例

---

## 📞 联系与资源

| 资源类型 | 链接 |
|----------|------|
| 🏠 组织主页 | [https://github.com/BeCrafter](https://github.com/BeCrafter) |
| 🚀 项目演示 | [http://iskill.site](http://iskill.site) |
| 🐛 问题反馈 | [Issues](https://github.com/BeCrafter/.github/issues)（对应项目下提交） |

---

<p align="center">
  🌟 欢迎 Star 收藏，关注工具生态迭代进展！
</p>
