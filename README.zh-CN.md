[English](README.md) · **简体中文**

# 高冷越 · glyahh

**AI Agent 工程实践 / Java & Python 后端**

计算机本科在读，寻找 AI Agent / AI 应用开发实习。

我在做 AI 应用和开发工具，关注工具调用、上下文管理，以及生成结果的验证与交付。也在探索 AI 与金融研究的结合。

## 代表项目

### [应用魔方 · app-cube](https://github.com/glyahh/app-cube)
Agent 驱动的应用开发工作台。以 Java 管理鉴权、应用任务与运行状态，由 Python DeepAgents / LangGraph 执行代码生成、增量修改和上下文管理；通过 WebSocket 实时交互，并结合 Docker 管理执行环境。已有项目导入与验证驱动的修复闭环仍在持续开发。

Java · Spring Boot · Python · DeepAgents · LangGraph · PostgreSQL · Docker

[重构分支源码](https://github.com/glyahh/app-cube/tree/agent_next)

### [Prism · 本地模型网关控制台](https://github.com/glyahh/Agent-router-Pro-Max/tree/main/app)
基于 CLIProxyAPI 构建控制台，管理网关启停、模型路由、配置与用量。我的工作聚焦控制台和客户端集成，推理转发由上游网关负责。

[查看项目](https://github.com/glyahh/Agent-router-Pro-Max/tree/main/app) · [设计决策](https://github.com/glyahh/Agent-router-Pro-Max/tree/main/docs/adr)

### [Finance Analysis Max · 金融研究工具](https://github.com/glyahh/Finance-Analysis-Max)
通过 MCP / REST 提供研究工具，组织可追溯证据并计算收益、波动和回撤等指标。

Python · MCP · 数据校验

[查看项目](https://github.com/glyahh/Finance-Analysis-Max)

## 开源贡献

### [CC-Switch · PR #7774](https://github.com/farion1231/cc-switch/pull/7774)
修复 Codex fork 会话的用量归集问题，排除继承历史造成的重复计费，并补充 11 项回归测试。

PR 记录了修复前后对照、重复扫描幂等性与跨平台预检结果。

**已提交，尚未合并** · 状态核对：2026-10-08

## 正在探索

- Coding Agent 的执行约束、上下文管理与结果验收
- 多模型客户端接入与本地开发工具
- AI 辅助金融研究与证据校验
