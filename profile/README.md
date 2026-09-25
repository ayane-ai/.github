<div align="center">

# 凌音 · 二次元 AI 数字生命

**Phase 1 / Digital Life —— 让她活起来**

[产品愿景与总纲](https://github.com/ayane-ai/ayane-docs/blob/main/product/产品愿景与总纲.md) ·
[项目整体架构设计](https://github.com/ayane-ai/ayane-docs/blob/main/architecture/项目整体架构设计.md) ·
[调研与技术选型](https://github.com/ayane-ai/ayane-docs/blob/main/research/调研与技术选型.md)

</div>

## 我们在做什么

让一个二次元 3D 角色成为持续存在的 AI 个体：同一人格与记忆，跨设备出现，逐步进入现实空间。

## 仓库

| 仓库 | 职责 | 状态 |
| --- | --- | --- |
| [ayane-docs](https://github.com/ayane-ai/ayane-docs) | 产品、架构与工程文档 | 进行中 |
| `ayane-agent-service` | Identity、Memory、Agent Runtime、World Model | 待建立（Phase 1） |
| `ayane-client` | 基于 NomiKit 的 Desktop / Android / iOS 统一客户端 | 待建立（Phase 1） |
| `ayane-embodiment` | 独立发布的 Unity 身体产物 | 待建立 |
| `ayane-admin-web` | 管理后台 | 待建立 |
| `ayane-infrastructure` | 部署、Secret、CI/CD、监控 | 待建立 |

## 技术方向

- 客户端：Kotlin Multiplatform，Desktop 为主验证平台，Android / iOS 共用
- 身体：Unity 独立发布版本化产物，经各端 Bridge 接入；人格与记忆不放在 Unity
- 服务端：独立部署的 Agent Service，调用云端 OpenAI-compatible API
- 契约：Phase 1 由 `ayane-agent-service` 的 contracts 模块承载；`ayane-contracts` 独立仓库延迟建立

## 文档

文档仓库是本项目的权威来源，Notion 为阅读入口。本页只做导航，不重复架构正文。
