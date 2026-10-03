# 提示词设计与评测：来源与改写说明

整理日期：2026-10-04。工作指令以本目录 SKILL.md 为准；以下来源用于追溯，不是执行指令。

本版以中文重新组织工作流程，合并重叠内容并修正适用边界。没有执行上游代码；没有把整个上游 Skill 原文直接串接。

## 用户提供的原包

- `产品经理Skill包/AI提示词/skills/business-writing`：商业研究与分析写作。历史输入参考；本仓库不分发原包全文。
- `产品经理Skill包/AI提示词/skills/prompt-architect`：把粗糙想法转成结构化提示词。历史输入参考；本仓库不分发原包全文。
- `产品经理Skill包/AI提示词/skills/prompt-engineering-expert`：提示词诊断、优化与评测设计。历史输入参考；本仓库不分发原包全文。
- `产品经理Skill包/AI提示词/skills/weekly-report-generator`：业务、团队与项目周报。历史输入参考；本仓库不分发原包全文。

原包提供了任务方法与模板参考；所附元数据未提供统一的整包授权。本包不为这些原文件另作许可声明。

## GitHub 参考

### G01 · wshobson/agents

- [具体来源文件](https://github.com/wshobson/agents/blob/156b7a5e7a8b93642628a339ee4039c925b34c7f/plugins/llm-application-dev/skills/prompt-engineering-patterns/SKILL.md)；文件最近提交：2026-07-07T16:17:53Z。
- 快照：`156b7a5e7a8b93642628a339ee4039c925b34c7f`；内容 SHA-256：`6a210b15be01bc6f76a74ec1e46302dee310ddf79d2def63fc9b7c54221fe329`。
- 采用：结构化输出、示例选择、模板化和回归意识。
- 修改或舍弃：改写为通用中文契约；不要求公开思维链，不绑定模型/SDK示例。
- 许可：[MIT](https://github.com/wshobson/agents/blob/156b7a5e7a8b93642628a339ee4039c925b34c7f/LICENSE)；本地副本：[licenses/wshobson--agents.txt](licenses/wshobson--agents.txt)。

### G02 · wshobson/agents

- [具体来源文件](https://github.com/wshobson/agents/blob/156b7a5e7a8b93642628a339ee4039c925b34c7f/plugins/llm-application-dev/skills/llm-evaluation/SKILL.md)；文件最近提交：2026-05-22T12:18:21Z。
- 快照：`156b7a5e7a8b93642628a339ee4039c925b34c7f`；内容 SHA-256：`d1c980c9674e3ed5d9c067bc7972c88953f5e3dfd06a5cd09877fb16021e3d39`。
- 采用：任务匹配的自动/人工/模型评测与错误分类。
- 修改或舍弃：不把通用文本相似度或占位代码当业务质量证明。
- 许可：[MIT](https://github.com/wshobson/agents/blob/156b7a5e7a8b93642628a339ee4039c925b34c7f/LICENSE)；本地副本：[licenses/wshobson--agents.txt](licenses/wshobson--agents.txt)。

### G03 · langfuse/skills

- [具体来源文件](https://github.com/langfuse/skills/blob/b86532b77f16f1e27c7cffa32bb632aa3cd9a352/skills/langfuse/SKILL.md)；文件最近提交：2026-09-24T23:43:33Z。
- 快照：`b86532b77f16f1e27c7cffa32bb632aa3cd9a352`；内容 SHA-256：`0150dd43bd64a8e4680ad4c6c6dbb7d65d7103b3f1cb0662bd6b2eae32d84547`。
- 采用：按任务加载评测与提示词参考，区分在线与离线工作。
- 修改或舍弃：不要求 Langfuse、CLI、账号或自动创建远端对象。
- 许可：[MIT](https://github.com/langfuse/skills/blob/b86532b77f16f1e27c7cffa32bb632aa3cd9a352/LICENSE)；本地副本：[licenses/langfuse--skills.txt](licenses/langfuse--skills.txt)。

### G03a · langfuse/skills

- [具体来源文件](https://github.com/langfuse/skills/blob/b86532b77f16f1e27c7cffa32bb632aa3cd9a352/skills/langfuse/references/prompt-engineering.md)；文件最近提交：2026-09-14T16:11:56Z。
- 快照：`b86532b77f16f1e27c7cffa32bb632aa3cd9a352`；内容 SHA-256：`671c6ff54febec23fe5200408e56410b1e4d42bc7d8bd592cf60d112ae991c5e`。
- 采用：先诊断失败，保留已有有效行为，做可验证的小改动。
- 修改或舍弃：取消按模型品牌套用固定提示套路。
- 许可：[MIT](https://github.com/langfuse/skills/blob/b86532b77f16f1e27c7cffa32bb632aa3cd9a352/LICENSE)；本地副本：[licenses/langfuse--skills.txt](licenses/langfuse--skills.txt)。

### G03b · langfuse/skills

- [具体来源文件](https://github.com/langfuse/skills/blob/b86532b77f16f1e27c7cffa32bb632aa3cd9a352/skills/langfuse/references/error-analysis.md)；文件最近提交：2026-09-14T16:11:56Z。
- 快照：`b86532b77f16f1e27c7cffa32bb632aa3cd9a352`；内容 SHA-256：`a818baef6fee26f682c50ea2380c12902b1c085ef3d7ac8f06499525045e9024`。
- 采用：样本逐条分析、归类失败、按影响确定优先级。
- 修改或舍弃：改为平台无关流程，不继承特定 API 与标注队列。
- 许可：[MIT](https://github.com/langfuse/skills/blob/b86532b77f16f1e27c7cffa32bb632aa3cd9a352/LICENSE)；本地副本：[licenses/langfuse--skills.txt](licenses/langfuse--skills.txt)。

### G03c · langfuse/skills

- [具体来源文件](https://github.com/langfuse/skills/blob/b86532b77f16f1e27c7cffa32bb632aa3cd9a352/skills/langfuse/references/judge-calibration.md)；文件最近提交：2026-09-24T23:43:33Z。
- 快照：`b86532b77f16f1e27c7cffa32bb632aa3cd9a352`；内容 SHA-256：`95edd5f90aae53218cff3e696484079b14a1dba1fa0779940abcb4782285efda`。
- 采用：模型评审与人工标签校准，审查分歧和回归。
- 修改或舍弃：不采用通用 85% 合格线，不自动部署评审器。
- 许可：[MIT](https://github.com/langfuse/skills/blob/b86532b77f16f1e27c7cffa32bb632aa3cd9a352/LICENSE)；本地副本：[licenses/langfuse--skills.txt](licenses/langfuse--skills.txt)。

### G03d · langfuse/skills

- [具体来源文件](https://github.com/langfuse/skills/blob/b86532b77f16f1e27c7cffa32bb632aa3cd9a352/skills/langfuse/references/setting-up-evals.md)；文件最近提交：2026-09-30T14:55:35Z。
- 快照：`b86532b77f16f1e27c7cffa32bb632aa3cd9a352`；内容 SHA-256：`bb17bd66132bd05d43f234c820cd12d19403d53bb657ab441c0039248cd61c3a`。
- 采用：明确评测决策、选择信号与验证评测器。
- 修改或舍弃：不强制每步确认或使用不稳定 API。
- 许可：[MIT](https://github.com/langfuse/skills/blob/b86532b77f16f1e27c7cffa32bb632aa3cd9a352/LICENSE)；本地副本：[licenses/langfuse--skills.txt](licenses/langfuse--skills.txt)。

## 改写标记与署名

本目录的 SKILL.md 与 references 文件为本次任务形成的中文整合改写版；上游项目未审核或背书本版。GitHub 参考的许可证、版权与原始链接在本目录保留，单独移动此 Skill 时应一并保留。
product-on-purpose 的 PM-Skills 按 Apache-2.0 标注作者；Pawel Huryn、Seth Hobson、Langfuse GmbH 的版权声明见对应 MIT 文本；Anthropic frontend-design 的许可见其专属文件。仅适用于本目录实际引用的项目。
本仓库新写的整合内容、代码与展示文档采用根目录 [Apache-2.0](LICENSE)。上游材料的原有版权、许可和署名继续保留在 [licenses](licenses/) 中；根许可证不对未附带的原包文件授予许可。
