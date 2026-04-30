# sb7-storybrand

SB7 (StoryBrand 7) 框架优化器 — 把 Donald Miller 的 StoryBrand 七元素作为**商业咨询方案 / 品牌话语 / 销售文案**的诊断与重构引擎。

> 客户是英雄，咨询师 / 品牌是向导。

## 触发场景

- 商业咨询方案、品牌定位草稿、销售话术、提案 PPT、官网首屏、产品介绍页
- "这个方案能不能优化"、"客户看不懂"、"卖不出去"、"差异化不够"

## 输出

每次调用产出 6 块结构化结果：

1. **SB7 诊断表** — 13 个细项标 ✅/⚠️/❌
2. **BrandScript 一页骨架** — 七元素填充
3. **一句话脚本** — `帮 [客户] 解决 [问题]，让他们 [成功画面]`
4. **重构后的方案大纲** — 按 SB7 叙事顺序（钩子 → 利害 → 向导 → 计划 → CTA）
5. **5 句即用文案** — 钩子/CTA/对比/保证/画面
6. **Grunt Test 结果** — 5 秒内能否回答"提供什么 / 怎么变好 / 怎么获取"

## 文件

- [SKILL.md](SKILL.md) — 主入口，6 步工作流 + 输出契约 + Anti-Patterns
- [references/sb7-elements.md](references/sb7-elements.md) — 七元素深度展开 + 反例库
- [references/consulting-rewrite-template.md](references/consulting-rewrite-template.md) — 5 段叙事重构模板
- [examples/before-after-saas.md](examples/before-after-saas.md) — SaaS 咨询提案 before/after 完整工作样例

## 安装

克隆到 `~/.claude/skills/`（Claude Code）或对应 Codex skill 目录：

```bash
git clone git@github.com:moonstachain/sb7-storybrand.git ~/.claude/skills/sb7-storybrand
```

## 来源

- 原书：Donald Miller, *Building a StoryBrand* (HarperCollins Leadership, 2017)
- 中译：《你的顾客需要一个好故事》（中国人民大学出版社, 2018）
- 配套：Donald Miller, *Marketing Made Simple* (2020)
- BrandScript 工具：mystorybrand.com
