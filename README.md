# 休闲小游戏产品设计专家

这是一个可安装的 Agent Skill。用《羊了个羊》拆解怎样降低首局理解成本、让失败有反馈、做同题社交、设计回访节拍，并验证商业化能否保留完整游玩体验。案例也保留团队失败、广告争议和近期证据的空白。

## 在 Codex 中使用

从目标项目目录运行：

```sh
git clone https://github.com/hrr198332897-tech/casual-mini-game-product-design.git .agents/skills/casual-mini-game-product-design
```

也可以从 GitHub 下载 ZIP，解压后将包含 `SKILL.md` 的文件夹命名为 `casual-mini-game-product-design`，放进项目的 `.agents/skills/`。用户级安装可使用个人目录下的 `.agents/skills/`。打开 Codex 的技能选择器，或在聊天中输入以下调用。若列表未刷新，重新打开 Codex。

> 用 $casual-mini-game-product-design 评审我的休闲小游戏。当前首局完成率 60%，首败重开率 38%，D1 11%。本周一个策划、一个前端。请给一个优先改动、最小验证和停止条件。

如果只研究案例，可直接问它「用 $casual-mini-game-product-design 拆解《羊了个羊》第二关，区分同期观察、张的说法和可迁移推断」。把平台、用户来源、版本、队列分母和本周资源一起提供，结论会更具体。

其他 Agent Skills 运行时，把完整目录放入该运行时的技能扫描位置，使用名称 casual-mini-game-product-design 调用。项目为纯 Markdown/YAML，日常用法无需联网、API 密钥或 Nuwa 安装。查核外链或当下平台政策时，如具备浏览能力可访问来源原文。 [OpenAI 本地 Skill 文档](https://learn.chatgpt.com/docs/build-skills#where-codex-loads-local-skills) · [Agent Skills 规范](https://agentskills.io/specification)

## 文件入口

- [SKILL.md](SKILL.md) 是运行时入口，带可操作招式和案例索引。
- [案例库](references/casebook.md) 先拆五层循环，再按 17 张案例卡查出处、局限与操作。
- [表达档案](references/voice.md) 保留八段可定位短引和适用语境。
- [研究底稿](references/research/README.md) 提供六路证据、履历、先验、跨域检验及独立题面。
- [FIDELITY.md](FIDELITY.md) 记录证据边界和验证结果。

## 方法来源与许可

研究采用花叔 Huashu 的 Nuwa 2.0.2 流程。项目以公开资料为基础，由本仓库独立整理。 [Nuwa 上游](https://github.com/alchaincyf/nuwa-skill) · [固定版本与验证方法](FIDELITY.md)

仓库原创内容按 [MIT 许可证](LICENSE) 开源。资料中的第三方引文、作品名称及外链内容依其原有权利归属。
