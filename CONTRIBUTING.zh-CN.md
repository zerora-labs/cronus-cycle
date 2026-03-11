# 参与 CronusCycle 贡献指南

首先，感谢你考虑为 CronusCycle 做出贡献。正是像你这样的人，让 CronusCycle 成为一个如此优秀的项目。

## 行为准则

本项目及所有参与人员均需遵守我们的[行为准则](CODE_OF_CONDUCT.md)。参与即表示你同意遵守该准则。

## 重要：贡献者许可协议（CLA）

**所有对本项目的贡献必须在有效的贡献者许可协议（CLA）下提交。**

### 为什么需要 CLA？

CronusCycle 采用 **Open Core** 模式：
- 核心框架基于 **MIT 许可证** 开源
- 高级功能在 **CronusCycle Enterprise**（商业闭源版本）中提供

为了保障项目的长期可持续发展，并允许我们将社区贡献同时用于开源核心和商业版本，**每位贡献者必须在合并 Pull Request 之前签署 CLA**。

### 如何签署 CLA

1. 当你提交第一个 Pull Request 时，我们的 CLA 机器人会自动评论并附上链接。
2. 点击链接，审阅协议内容，并在线签署（一次签署，终身有效）。
3. 签署完成后，你的 PR 即可进入审核流程。

如果你希望手动签署，可以从 [CLA.md](CLA.md) 下载协议，并将签署后的扫描件发送至 [bruce@zerora.cn](mailto:bruce@zerora.cn)。

## 如何贡献？

### 报告 Bug

- 先在 [Issues](https://github.com/zerora-labs/cronus-cycle/issues) 中搜索，确认该 Bug 尚未被报告。
- 如果未找到，[创建新 Issue](https://github.com/zerora-labs/cronus-cycle/issues/new)，并提供清晰的标题、描述、相关环境信息，以及可复现的代码示例。

### 建议新功能

- 创建新 Issue 描述你的建议。
- 清晰说明该功能的价值和适用场景。

### 你的第一个代码贡献

可以从标注了 `good-first-issue` 或 `help-wanted` 的 Issue 入手。

### Pull Request 流程

1. **Fork** 本仓库，并从 `main` 分支创建你的特性分支。
2. **签名提交** – 所有提交必须使用 GPG 签名（`git commit -S`）。
3. **添加测试** – 新增代码需包含测试；修复 Bug 需添加能捕获该 Bug 的测试。
4. **更新文档** – 确保功能变更同步更新文档。
5. **确保测试通过** – 本地运行 `npm test`。
6. **保持 PR 聚焦** – 一个 PR 只解决一个问题，便于审核。
7. **关联 Issue** – 在 PR 描述中使用“Fixes #123”自动关闭相关 Issue。

## 规范指南

### Git 提交信息

我们遵循 [Conventional Commits](https://www.conventionalcommits.org/zh-hans/) 规范：

- **格式**：`<类型>(<范围>): <描述>`
- **类型**：`feat`、`fix`、`docs`、`style`、`refactor`、`test`、`chore`
- **示例**：`feat(galaxy-engine): 添加黑洞风险可视化`

所有提交必须包含 **Signed-off-by** 行（`git commit -s` 自动添加），证明你有权提交该作品。

### 代码风格

- 使用 **Prettier** 进行代码格式化。
- 提交前运行 `npm run lint` 检查代码风格。

## 获取帮助

- GitHub Issues：[https://github.com/zerora-labs/cronus-cycle/issues](https://github.com/zerora-labs/cronus-cycle/issues)
- 邮箱：[bruce@zerora.cn](mailto:bruce@zerora.cn)

感谢你为 CronusCycle 做出贡献！