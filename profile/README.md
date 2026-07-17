# KDevSec

安全研发组织 —— AI 数字员工、Claude Code 插件生态、安全加固方案与研发流程工程化。

---

## 🏗 平台

| 仓库 | 可见性 | 描述 | 主要作者 |
|---|---|---|---|
| [Keyhub](https://github.com/KDevSec/Keyhub) | 私有 | AgentHub - 数字资产统一管理与共享平台 | ly1989abc, vsxd, dongmucat, yun-zhi-ztl, ljccc-rbs |
| [token-statistics](https://github.com/KDevSec/token-statistics) | 私有 | TokenManager平台 - AI 编程工具研发效能度量底座 | ly1989abc |
| [ClawSecurity](https://github.com/KDevSec/ClawSecurity) | 私有 | ClawManager 加固方案主仓，含 ClawAegis / ClawManager / secureclaw 三个子项目 | TC-fighting |
| [KSecForAIDemo](https://github.com/KDevSec/KSecForAIDemo) | 私有 | KSecForAI 交互原型集：围绕 OpenClaw 智能体安全治理，涵盖输入面 / 状态面 / 决策面 / 输出面 / 资产防护 / 应急熔断 / 出站治理等 13 个安全防护场景 | TC-fighting |
| [ksec-bridge](https://github.com/KDevSec/ksec-bridge) | 私有 | ClawManager 加固方案中，界面与 KSec 标准版通信的中间件 | TC-fighting |
| [sop_test0518](https://github.com/KDevSec/sop_test0518) | 私有 | KDevSec实际开发仓库，前期为SOP流程第二轮测试 | ljccc-rbs, TC-fighting |
| [KDevSec](https://github.com/KDevSec/KDevSec) | 私有（已废弃） | KDevSec早期开发仓库，后来废弃，改用sop_test0518 | ljccc-rbs |
| [SOP_test](https://github.com/KDevSec/SOP_test) | 私有 | SOP第一轮测试 | ly1989abc, doudoudou-dou |

## 🔌 PLUGIN/SKILL

| 仓库 | 可见性 | 描述 | 主要作者 |
|---|---|---|---|
| [ieidev-team](https://github.com/KDevSec/ieidev-team) | 私有 | ieidev 数字员工套件——自包含单插件（编排引擎 + 记忆底座 + Agent + skill），一包多宿主（当前支持claude code、opencode、codebuddy） | ly1989abc |
| [kdev-agents](https://github.com/KDevSec/kdev-agents) | 公开 | KDev 系列 Claude Code 插件集合，本身即 plugin marketplace。含工程记忆（已转移到ieidev-team中）、AI commit、安全编码规范、代码图谱、设计流程编排、测试点/用例/API 自动化等 12 个插件 | ly1989abc, ljccc-rbs, doudoudou-dou, TC-fighting |
| [kdev-skill](https://github.com/KDevSec/kdev-skill) | 私有 | 标准化开发流程编排技能：纯 SKILL.md 薄编排层，提供 IR→SR→AR→TDD 流程强制指引 | ly1989abc |
| [html-to-pptx](https://github.com/KDevSec/html-to-pptx) | 公开 | Claude skill：把自包含 HTML 页转成高保真、**可编辑**的 PowerPoint (.pptx)。原生形状/文字 + 透明 PNG 切图混合，跨 PowerPoint / Keynote / LibreOffice / Slides | ly1989abc |

## 📦 发布分发

| 仓库 | 可见性 | 描述 | 主要作者 |
|---|---|---|---|
| [ieidev-team-release](https://github.com/KDevSec/ieidev-team-release) | 公开 | ieidev-team 数字员工套件公开发布/分发仓，npm 装机包 `npx ieidev-team`（插件本体源码私有维护） | ly1989abc |
| [token-stats-releases](https://github.com/KDevSec/token-stats-releases) | 公开 | TokenManager平台公开发布分发 | ly1989abc |

## 🧠 工程记忆

| 仓库 | 可见性 | 描述 | 主要作者 |
|---|---|---|---|
| [ieidev-team-memory](https://github.com/KDevSec/ieidev-team-memory) | 私有 | ieidev-team 工程记忆仓：决策 / 踩坑 / 执行 / 改进日志 | ly1989abc |
| [kdev-agents-memory](https://github.com/KDevSec/kdev-agents-memory) | 私有 | kdev-agents 工程记忆仓：决策 / 踩坑 / 执行 / 改进日志 | ly1989abc |

## 🛠 脚本

| 仓库 | 可见性 | 描述 | 主要作者 |
|---|---|---|---|
| [claude-auto-resume](https://github.com/KDevSec/claude-auto-resume) | 公开 | CC用量限制解除后自动续跑 Claude CLI 任务的 Shell 工具。fork 自 [terryso/claude-auto-resume](https://github.com/terryso/claude-auto-resume) | 上游 terryso；本仓 ly1989abc |

---

<sub>共 17 个仓库（5 公开 · 12 私有）。作者按 commit 贡献量排序。</sub>
