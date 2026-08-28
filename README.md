# 孙学 · Sunxue

> 情绪是证据的利息。你只能出示本金——动作、数字、物件、空间——利息由读者自己结算。

源自孙宇晨《我的女友景甜》的**极简白描叙事写作法**，蒸馏为一个即装即用的 AI Agent Skill。

2026 年 8 月，孙宇晨以 XeLaTeX 排版发布七千字长文《我的女友景甜》([HEJustinSun/my-girlfriend-jingtian-latex](https://github.com/HEJustinSun/my-girlfriend-jingtian-latex))。一个以营销浮夸著称的人拿出了克制到冷酷的文学作品，这种反差让"孙学"一词成为这套写法的名字。社区评价：*"大量白描和极度克制的情感表达，只要出现在新概念作文大赛中名次都不会低。"*

## 这个 Skill 教什么

十条从原文解剖出的技法：

| # | 技法 | 一句话 |
|---|------|--------|
| 1 | 天平开篇 | 前三句架起极轻与极重的对照 |
| 2 | 单句成段 | 段落短，段落群要厚 |
| 3 | 数字精确律 | 30天100万美元，住了8天 |
| 4 | 旁观者证词 | 让最不懂故事的人说出最懂故事的话 |
| 5 | 名词句判决 | "一座失去皇后的凡尔赛宫。" |
| 6 | 空间写情 | "她喜欢一个地方因为她而空着" |
| 7 | 物件押韵 | 最后一次出场必须带一次失败的尝试 |
| 8 | 数码物证 | 一条被划掉的日程提醒 |
| 9 | 倍率短句 | "没有五千万，不取" |
| 10 | 虚空收束 | "什么都没有发生" |

附完整写作流程、自检清单与一票否决红线。详见 [`sunxue/SKILL.md`](sunxue/SKILL.md)。

## 安装

```bash
# ZCode / Codex CLI
git clone https://github.com/bayshier/sunxue.git
cp -r sunxue/sunxue ~/.zcode/skills/sunxue
# 或软链
ln -s $(pwd)/sunxue/sunxue ~/.zcode/skills/sunxue
```

## 使用

对 AI 说：

> 用孙学写法，帮我写一篇关于 XX 的回忆长文

或直接触发：`孙哥风格` / `景甜式白描` / `冷叙事` / `克制到极致的故事`。

## 仓库结构

```
sunxue/
├── README.md
├── LICENSE                  # MIT（技能文本）
└── sunxue/                  # ← 安装这个目录
    ├── SKILL.md             # 技能主体：心法 + 十条技法 + 流程 + 红线
    ├── VERSION              # 1.0.0
    └── references/
        ├── style-anatomy.md # 原文逐条技法解剖（引文例证）
        └── background.md    # 孙宇晨其人、事件脉络、孙学一词来历
```

## 致谢与声明

- 原文版权归原作者所有，本技能仅摘引片段作文风分析；完整文本请读原仓库。
- 技能结构参考社区先行工作 [sun-style-writing](https://github.com/KKKKhazix/sun-style-writing)，技法体系与文本拆解为独立原创。
