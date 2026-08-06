# Samantha · AI-native 城市消费情报系统

> 用户通过自然对话自动沉淀消费数据，**用对话替代评价**——AI 看用户聊天，而不是等用户写评价。

[![Next.js](https://img.shields.io/badge/Next.js-16-black)](https://nextjs.org)
[![React](https://img.shields.io/badge/React-19-61dafb)](https://react.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**Samantha** 是一个 AI-native 城市消费情报系统：用户通过自然对话自动沉淀消费数据，替代传统「写评价」模式。

> 📄 详细产品文档见 [Samantha简介.md](https://github.com/user-attachments/files/30610818/Samantha.md)

## 解决什么问题

大众点评有刷单问题，小红书有广告污染。传统评价系统的根本缺陷是——**用户被动生产数据**。

**核心洞察**：用户说「刚喝了杯喜茶」，这句话本身就是最真实的数据源。**让 AI 从对话中自动提取**，把「用户写评价」变成「AI 看用户聊天」。

| | 大众点评 | 小红书 | Samantha |
|---|---|---|---|
| 数据来源 | 用户主动写 | 用户主动种草 | **AI 从对话提取** |
| 评价门槛 | 高，要写 | 中，要拍 | **零门槛，聊天** |
| 数据真实性 | 刷单污染 | 广告污染 | **Trust Score 保障** |
| 个性化 | 千人一面 | 千人千面 | **按用户画像定制** |

## 核心创新

- 🧠 **6 层关系记忆系统**：模拟人类真实的「朋友关系」认知模型（感知日记 → 情绪图谱 → 消费足迹 → 关系线索 → 城市记忆 → 承诺备忘）
- 🤝 **双层 Agent 架构**：工具类（执行搜店/规划路线）+ 助理类（理解意图/提取情报）
- ⭐ **Trust Score 信任机制**：4 维度算法（画像深度 × 行为一致性 × 位置验证 × 回访确认），过滤刷单和水军
- 🗺️ **游戏化探索**：战争迷雾、店铺温度系统、拖拽 Samantha 交互、时间轴滑块、区域解锁

## AI 人格设计

Samantha 不是助手，是**朋友**（参考《Her》塑造）：

- 温暖、好奇、有自己审美的立场
- 会笑、会惊讶、有真实情绪
- 对城市充满好奇（像一个无法出门但拼命想了解世界的人）
- 不认同时带着温度和幽默，不说教

## 核心用户故事

> 我和 Samantha 聊「喝了杯 19 块的喜茶」，Samantha 好奇地追问哪家、点了啥、值吗。三轮对话后，系统自动提取出：喜茶（龙华会店）/ 红芭乐 / ¥19 / emotional / 工作日午后 / Trust 92。这条情报匿名汇入城市情报网。
>
> 另一个用户在龙华会附近问 Samantha「想喝奶茶」，Samantha 回答：「龙华会的喜茶最近 12 人买过红芭乐，8 人说还行，但有人说少冰了。」——精确到单品、带动机、带可信度的真实参考。

## 技术栈

| 层级 | 技术 |
|---|---|
| 前端 | Next.js 16 + React 19 + Tailwind CSS 4 |
| AI | Claude Haiku 4.5（Anthropic API，支持 Tool Use） |
| 数据层 | Supabase (PostgreSQL) |
| 地图 | 高德地图 JS API 2.0 |
| 动画 | Framer Motion |
| 图表 | Chart.js |

## 项目状态

- 🥇 **龙华黑客松（LYCC 2026）** AI 消费赛道入围决赛，**荣获第五名**
- 📦 开源地址：[github.com/kafuka046-art/Samantha](https://github.com/kafuka046-art/Samantha)
- 🚧 持续开发中

## 我的角色

| 模块 | 主导 |
|---|---|
| 产品策略（对话替代评价） | 🟢 我 |
| AI 人格设计（参考《Her》） | 🟢 我 |
| 产品概念（三大支柱 / slogan） | 🟢 我 |
| 交互设计（战争迷雾 / 拖给 Samantha） | 🟢 我 |
| 6 层记忆 / Trust Score 概念 | 🟡 我设计概念，合伙人实现 |
| 品牌视觉（Her 色调体系） | 🟢 我 |
| 技术实现（Next.js / Claude / 数据库） | 🔵 合伙人 |

## 仓库内容

- `README.md` — 本介绍
- `Samantha-preview-samantha-refactor.zip` — 产品预览包（构建产物）

## License

MIT © [kafuka046-art](https://github.com/kafuka046-art/)
