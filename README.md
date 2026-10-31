# Open Agent Systems · Community profile

本仓库维护 Open Agent Systems 的公开组织介绍与品牌图片。

[中文官网](https://open-agent-systems.github.io/) · [English website](https://open-agent-systems.github.io/en/)

## 文件入口

- [中文主页](profile/README.md)：默认正文，展示在 GitHub 组织首页。
- [English](profile/README.en.md)：独立的英文介绍。
- [旧中文入口](profile/README.zh-CN.md)：保留历史链接，指向默认中文主页。
- [横版标识](assets/banner.jpg)：用于组织介绍。
- [方形头像](assets/avatar.jpg)：OAS 简称版本，用于组织头像。

## 多语言维护

每种语言独立维护一个文件，避免逐段混排。中文 `profile/README.md` 作为基准版本，英文维护在 `profile/README.en.md`；其他语言按 `profile/README.<语言标签>.md` 命名，例如日文 `README.ja.md`、繁体中文 `README.zh-TW.md`。这些只是命名示例，尚未提供相应翻译。

新增语言时：

1. 从中文基准复制正文，翻译为目标语言，保留事实、项目状态和有效链接。
2. 在所有已提供语言的文件顶部加入新语言链接，使用该语言的名称。
3. 语言导航使用完整 GitHub 文件链接，确保在组织主页和仓库文件页都能访问。
4. 更新项目状态时同步已有翻译；无法及时同步时，在对应译文注明差异并链接基准版本。
5. 检查图片、语言导航及项目链接后提交。

GitHub 组织首页使用 `profile/README.md`；其他语言通过顶部链接访问，不依赖自动语言切换。只为已存在的译文添加入口，不建立空白语言文件。

仅为实际公开的项目添加源码链接。本仓库不包含私有设计资料、运行配置或业务数据。

## 内容维护

组织介绍与官网保持定位一致：说明愿景、能力领域、建设方法和当前阶段。能力领域属于建设方向，不表述为已交付功能。项目正式公开后再添加介绍及源码入口，不提前公开内部设计或未发布项目细节。中英文保持相同事实与范围，组织头像与横幅独立维护。

## 架构图

`assets/diagrams/` 保存生态架构与任务闭环的可编辑 SVG，中英文分别以 `.zh-CN.svg`、`.en.svg` 命名。图中文字、可访问描述和正文保持同步；图上保留目标架构或目标流程说明。新增语言应同时翻译正文和图示。修改后检查两种语言的文字长度、连线和 GitHub 图片入口。
