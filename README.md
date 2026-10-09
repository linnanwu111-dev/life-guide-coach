# life-guide-coach · 高性价比人生指南 AI 用法

把《高性价比人生指南》交给 AI：直接查原书，或者先聊自己的处境，再选少量适合自己的行动，最后得到一张能执行、能查出处的行动概览图。

这是非官方 Skill。原书作者是 **eternity4719**，原项目：[eternity4719/HowToLiveBetter](https://github.com/eternity4719/HowToLiveBetter)。本仓库新增采访、候选筛选与本周／本月／本年安排规则，没有原作者背书，也不保证个人效果。

## 安装

当前测试版为 [v0.2.1](https://github.com/linnanwu111-dev/life-guide-coach/releases/tag/v0.2.1)。支持从 GitHub 安装技能的 AI 工作客户端，可以直接发送：

> 从 https://github.com/linnanwu111-dev/life-guide-coach 安装或更新 life-guide-coach，使用 v0.2.1 Release 的 Skill ZIP，保留 references 中的完整原文和行动图设计说明。读到 SKILL.md 后告诉我实际安装的版本；如果当前客户端无法安装，直接说明。

也可以下载上述 Release 的 ZIP，通过当前客户端的 Skill 导入功能安装。包内包含 `life-guide-coach/SKILL.md` 和所需原文。`releases/latest` 只指向稳定版，未必是当前测试版。

豆包工作实测：v0.1.0 能导入、启用并读取随附原文；v0.1.2 已由其工作助手从 GitHub 下载并报告更新，新会话确实先介绍指南范围再询问方向。运动示例经过追问和提示调整得到周／月／年安排，仍需检查助手是否提前推荐或增加未选择的任务。年度逐步加量和力量训练可以作为候选，但须结合条件、意愿与实际反馈。v0.2.1 新增视觉收尾；具体图片生成能力由当前会话的工具决定，发布规则本身不代表所有客户端均已实测通过。

其他客户端按其 Skill 安装方式使用。无法安装 Skill 时，也可以把 `SKILL.md` 与对应原文作为资料提供给能读文件的 AI；这需要自行确认文件确实读取成功。

## 怎么用

- 查书：“第4节主要讲什么？保留重要条件和出处。”
- 拿资料：“给我官方 PDF 和网页版。”
- 应用到自己：“我想改善一件事，但不知道先做哪一步。先了解我，再从这本指南里帮我选。”

首次个人计划先给指南范围与标注方式的简短总览，再问想改善哪方面。随后只问会改变选择的必要信息，给少量有出处的候选，等你选好后再安排第一步。周、月、年围绕同一方向，不需要凑满三项任务。没有长期意愿时，年度方向可以暂不确定；想逐步加量时，再结合实际反馈和适用条件选择。

方案明确后默认做行动概览图：当前卡点、本周动作、月度回看、年度方向和原书条目对应关系都在图中。优先用当前会话的内置图片生成；不可用时提供可编辑 SVG，或用已有网页渲染工具截图。实际检查文字和出处后才交付文件。只要文字时说“这次不用做图”即可；直接查书或拿资料不会强制制图。图片生成、SVG、HTML截图各有可直接使用的提示词，连同设计简报与交付规则见 [行动图设计说明](references/action-visual.md)。

## 原文与版本

本包随附原仓库 **34节、675条**及补充文档的完整 Markdown 快照，固定提交：[`2ad14690851994a0e1f45d6dc9b5a9d6aa1579a9`](https://github.com/eternity4719/HowToLiveBetter/tree/2ad14690851994a0e1f45d6dc9b5a9d6aa1579a9)。文件与校验值见 `references/original/source-manifest.json`。

默认按需读取随附原文；请求最新版本或缺少文件时，才访问原项目。不能把随附快照称为实时同步。

原文、作者标签与本 Skill 的排期设计分别标明。只根据已读取的原书推荐，资料不足时说明缺口。

## 许可与署名

《高性价比人生指南》正文作者 eternity4719，采用 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)。随附原文未经修改，原许可证保留在 `references/original/LICENSE`；原项目代码许可另见 `references/original/LICENSE-CODE`。

本仓库新增的 Skill 说明和导航也按 CC BY 4.0 分享，署名 linnanwu111-dev。转载或修改请保留原书作者、原项目链接、许可和改动说明。根目录 `LICENSE` 保留 CC BY 4.0 全文。
