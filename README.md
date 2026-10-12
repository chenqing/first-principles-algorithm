# First Principles Algorithm

把马斯克式的**第一性原理**与**五步工程算法**（质疑 → 删除 → 简化 → 加速 → 最后自动化）做成可调用的 Agent Skill。语气是工程审查，不是传记迷弟；不默认加班文化或心理不安全。

## 什么时候用

- 产品 / 流程 / 架构显得过度复杂、昂贵或过慢
- 继承来的需求被当成「神圣不可改」
- 团队过早优化或过早自动化
- 想从硬约束（物理、法规、真实信息边界）重新推一遍，而不是照搬行业惯例

## 什么时候别用

- 合规 / 安全底线还没和法律/可选流程拆开
- 以共情或心理安全为目标的人事决策
- 日常小改动，不值得做完整第一性原理重推

## 安装

```bash
npx skills add chenqing/first-principles-algorithm --skill first-principles-algorithm
```

或把 `skills/first-principles-algorithm/SKILL.md` 拷进你的 Agent skills 目录。

## 五步顺序（不可打乱）

1. **让需求别那么蠢** — 每个需求挂人名，谁提的都要质疑  
2. **拼命删除** — 零件、工序、功能、会议、层级；事后加回不到约 10% 说明删得不够  
3. **简化 / 优化** — 只优化删完还活着的东西  
4. **加快循环** — 缩短 build → test → learn；别加速浪费的流程  
5. **最后才自动化** — 前面不稳就自动化，会把浪费锁死  

## 一手来源（优先引用这些）

- [Everyday Astronaut Starbase 访谈](https://everydayastronaut.com/starbase-tour-and-interview-with-elon-musk/)（五步口述）
- [Kevin Rose Foundation 2012](https://elonmuskarchive.org/video/foundation-kevin-rose-2012-09-08)（第一性原理 + 电池例子）
- [WIRED / Chris Anderson 2012](https://www.wired.com/2012/10/ff-elon-musk-qa/)（火箭原材料约 2%）
- [USC 2014 毕业典礼](https://elonmuskarchive.org/video/usc-commencement-2014-05-16)
- Walter Isaacson《Elon Musk》(2023) 约 pp. 284–286
- [Lex Fridman #438](https://lexfridman.com/elon-musk-and-neuralink-team-transcript/)

## License

MIT
