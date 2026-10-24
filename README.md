# web-novel-writing · 网文写作技能

一个面向 AI Agent 的**网文/小说创作方法论技能包**，蒸馏自抖音两位头部写作博主的全套教程：

- **猫神写作** —— 117 讲纯写作教学（2025-09 ~ 2026-10）
- **码字如有神** —— 22 讲写作教学

涵盖从选题开书、大纲结构、人物文笔，到节奏爽点、卡文救场、拆书对标、AI 协作与职业决策的完整创作链路。

## 技能结构

```
├── SKILL.md                    # 入口：场景路由表 + 八条铁律 + 四步工作流
├── references/                 # 8 个按需加载的方法论模块
│   ├── 01-foundations.md       # 底层逻辑、期待感工程学、爽点设计、情绪心理学
│   ├── 02-opening-hooks.md     # 黄金三百字、危机应对法、十种模板、十大毒点、书名简介
│   ├── 03-outline-structure.md # 活大纲、逆推法、四级结构、伏笔管理、系统文三死穴
│   ├── 04-characters.md        # 人设三支柱、对话四招三坑、顶级反派、感情戏
│   ├── 05-prose-craft.md       # 展示不讲述、笔力公式、电影叙事、动作戏
│   ├── 06-pacing-conflict.md   # 信息分配权、断章艺术、卡文破局、高潮六招、反转三招
│   ├── 07-brainstorm-ai.md     # 脑洞四类、世界观三招、灵感五招、AI 去味
│   └── 08-market-career.md     # 选题八股文、拆书四维度、素材库、止损、七天签约、行动清单
└── assets/                     # 两个可直接套用的模板
    ├── chapter-card-template.md    # 章节卡（目标/冲突/钩子 + 自查四问）
    └── story-bible-template.md     # 故事圣经（一句话核心/四级结构/死敌链/伏笔备忘录）
```

## 安装

将整个目录复制为技能目录即可（目录名即技能名）：

```bash
# WorkBuddy / Claude 风格的用户级技能目录
cp -r web-novel-writing ~/.workbuddy/skills/

# 或项目级
cp -r web-novel-writing <项目>/.workbuddy/skills/
```

安装后，对话中涉及写小说、开新书、列大纲、人设、开篇、卡文、爽点/钩子、拆书、去 AI 味、网文商业化等需求时会自动触发。

## 核心方法论速览

**八条铁律**：

1. 网文是情绪产品，不是文学作品——市场先于表达，换位先于自嗨
2. 顶级网文是一个接一个的勾子——期待感（信息差）比爽点更重要
3. 爽的本质是过程不是结果
4. 黄金三百字——开篇第一句话就让主角活不下去
5. 主角的高度由反派的智商决定
6. 要展示，不要讲述
7. 慢要酝酿期待，快要留给爆发，张持有度，钩子断章
8. 数据不行就止损

详见 [SKILL.md](SKILL.md) 的场景路由表与各 references 模块。

## 模板

- [`assets/chapter-card-template.md`](assets/chapter-card-template.md) —— 每章开工前 5 分钟填好的章节卡
- [`assets/story-bible-template.md`](assets/story-bible-template.md) —— 开书时一次搭好的故事圣经

## 来源

全部内容提炼自公开短视频教程，已按主题重组、去重、补齐执行细节；原视频中博主个人经验之谈仅供参考，请结合自身创作阶段取舍。

## License

MIT
