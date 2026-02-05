# BeCrafter - 高效开发者工具生态


👋 专注于打造 轻量、实用、可复用 的开发者工具套件，覆盖 AI 提示词管理、分布式系统、数据处理等核心场景

---

## 🎯 核心项目矩阵

### 🔧 AI 提示词生态工具

|项目名称|核心功能|技术栈|状态|
|---|---|---|---|
|[prompt-manager](https://github.com/BeCrafter/prompt-manager)|MCP 协议 Prompt 管理服务，支持流式传输 + 双端管理|TypeScript + MCP|✅ 稳定迭代|
|[PromptCraft](https://github.com/BeCrafter/PromptCraft)|高质量 AI 提示词库展示平台|React + Node.js|🚀 持续更新|
|[prompt-mcp](https://github.com/BeCrafter/prompt-mcp)|MCP 协议兼容服务器，支持本地 / 远程对接|JavaScript|✅ 生产可用|
### ⚡ 分布式与系统工具

|项目名称|核心功能|技术栈|状态|
|---|---|---|---|
|[go-ratelimiter](https://github.com/BeCrafter/go-ratelimiter)|4 种限流机制（固定窗口 / 滑动窗口 / 漏桶 / 令牌桶）|Go + Redis + Lua|✅ 生产可用|
|[sync-hub](https://github.com/BeCrafter/sync-hub)|一源多目标文件同步，智能降级|JavaScript|🚧 开发中|
### 📊 数据处理工具

|项目名称|核心功能|技术栈|状态|
|---|---|---|---|
|[json2image](https://github.com/BeCrafter/json2image)|JSON 数据可视化，规则化图片生成|Go|✅ 稳定迭代|
|[go-parser](https://github.com/BeCrafter/go-parser)|轻量级规则引擎，基于 Golang 语法解析|Go|✅ 生产可用|
### 🛠️ 工具集封装

|项目名称|核心功能|技术栈|状态|
|---|---|---|---|
|[commander](https://github.com/BeCrafter/commander)|命令行多工具封装，集中管理分散工具|Go + CLI|✅ 稳定迭代|
---

## 📋 技术栈全景



### 核心技术栈

- **编程语言**：Go（后端核心）、TypeScript/JavaScript（前端 / 工具链）

- **中间件 / 协议**：Redis（缓存 / 分布式）、Lua（脚本引擎）、MCP 协议（Prompt 传输）

- **开发规范**：RESTful API 设计、TDD 测试驱动、语义化版本控制

- **开源协议**：MIT License（全项目开源，商用友好）

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

|资源类型|链接|
|---|---|
|组织主页|[https://github.com/BeCrafter](https://github.com/BeCrafter)|
|项目演示|[http://iskill.site](http://iskill.site)|
|问题反馈|[Issues](https://github.com/BeCrafter/xxx/issues)（对应项目下提交）|

---

🌟 欢迎 Star 收藏，关注工具生态迭代进展！
