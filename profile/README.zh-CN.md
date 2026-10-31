<p align="center">
  <img src="https://raw.githubusercontent.com/Open-Agent-Systems/.github/main/assets/banner.jpg" alt="Open Agent Systems" width="900" />
</p>

[English](https://github.com/Open-Agent-Systems/.github/blob/main/profile/README.md) · **简体中文**

# 共建 AI 原生系统的开放基础

**Open Agent Systems（OAS）** 是一个围绕 AI 原生系统与云原生基础设施开展建设的开源组织。我们希望连接模型、智能体、工具、知识与运行环境，让开发者能够组合独立能力，构建可运行、可管理、可持续改进的系统。

[访问官网](https://open-agent-systems.github.io/zh/) · [探索能力体系](https://open-agent-systems.github.io/zh/#architecture) · [参与讨论](https://github.com/Open-Agent-Systems/.github/issues)

## 我们为什么做这件事

从一次模型调用到完成真实工作，需要的不只是模型能力。任务需要编排与恢复，执行需要隔离与权限，知识需要来源与更新，产出需要验证，积累的能力还需要复用。

我们希望让这些基础能力通过清晰接口协作，让团队减少重复集成，把更多精力投入研发交付、智能运维和业务自动化。同时保留对模型、工具与部署环境的选择权。

## 我们希望建设什么

以应用需求为起点，以智能体执行为核心，知识与资产支撑复用，安全治理与评测贯穿全过程。

[![目标生态架构：能力分层与贯穿式治理](https://raw.githubusercontent.com/Open-Agent-Systems/.github/main/assets/diagrams/ecosystem.zh-CN.svg)](https://raw.githubusercontent.com/Open-Agent-Systems/.github/main/assets/diagrams/ecosystem.zh-CN.svg)

| 能力领域 | 建设重点 |
| --- | --- |
| 模型服务与网关 | 模型代理、接入与路由、降级、配额与用量计量。 |
| 智能体构建与协作 | 任务编排、工具调用、多智能体协作与人工介入。 |
| 运行环境与沙箱 | 隔离执行、调度与恢复、资源及环境生命周期管理。 |
| 上下文、状态与知识 | 上下文工程、任务检查点、记忆、知识来源与访问边界。 |
| AI 资产与供应链 | Prompt、Skill、工具与模板的注册发现、版本分发、来源与依赖管理。 |
| 安全与治理 | 身份授权、策略审批、预算控制与审计。 |
| 评测与持续优化 | 执行轨迹、回放、质量与成本评估、结果验证。 |
| 开发体验与应用 | SDK、CLI、调试交付，以及真实场景中的应用实践。 |

开放接口、能力描述和兼容性验证是这些领域协作的共同基础。长期而言，我们希望能力能够在本地、私有云、公有云和边缘环境中组合使用。

以上是生态建设方向，不代表所有能力已经交付，也不是单个产品的功能清单。具体实现、支持范围与验证结果以正式公开项目的文档为准。

## 从目标到可验证的交付

任务沿目标、规划、执行、验证和交付推进。审批与检查点约束执行；验证未通过时调整计划；经筛选、验证的产出沉淀为后续任务可复用的资产。

[![目标任务闭环：执行、验证、恢复与资产复用](https://raw.githubusercontent.com/Open-Agent-Systems/.github/main/assets/diagrams/task-cycle.zh-CN.svg)](https://raw.githubusercontent.com/Open-Agent-Systems/.github/main/assets/diagrams/task-cycle.zh-CN.svg)

## 怎样推进

从有独立使用价值的组件做起，在实际使用中验证，再通过接口逐步形成可组合的系统。我们重视：

- **清晰的边界**：项目可以独立使用，也能与其他工具协作。
- **可验证的结果**：说明已经实现、已经验证和尚在探索的内容。
- **可持续的维护**：文档、示例、兼容性与维护成本同样是交付的一部分。
- **开放的协作**：依据使用场景和社区反馈调整优先级，不预设所有能力都由一个项目实现。

## 当前进展与参与方式

组织仍处于早期建设阶段，官网已提供愿景、能力体系与演进方向。项目将在具备公开条件后单独发布，并在这里补充入口。

欢迎开发者、维护者和使用团队通过[社区 Issues](https://github.com/Open-Agent-Systems/.github/issues)交流：

- 你希望 AI 完成什么工作，现有方案在哪里遇到阻碍？
- 哪些基础能力值得共享，哪些接口需要互通？
- 你愿意参与哪些实践验证、文档、翻译或项目协作？

提出场景时，请尽量说明运行环境、约束和预期结果。具体项目发布后，功能建议、问题报告和代码贡献请前往对应仓库。
