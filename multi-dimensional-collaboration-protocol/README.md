# 多维协作协议
## Multi-Dimensional Collaboration Protocol (MDCP)

> 一套共享的认知框架。人类用它来理解 AI 并校准通信，AI 用它来理解人类并引导自己。

---

## English

A shared cognitive framework for human-AI collaboration.

**The core insight**: AI excels at single-dimension optimization but structurally lacks time awareness, value judgment, and meta-cognition. It cannot feel how long something has taken, cannot tell "can do" from "worth doing," and cannot see when it's locked into a wrong direction. The human who built this protocol compensates for these blind spots by calibrating their communication — giving observations without diagnoses, sketching architecture in natural language, using precision shifts as trust signals. This protocol gives the AI the same framework so both sides share a common cognitive model.

**What's inside**: an honest analysis of AI's cognitive architecture (§1-§2), the communication patterns that naturally emerge from it (§3-§4), and 11 executable behavioral rules derived from the framework (§5). The skill file is in Chinese because the signal patterns it encodes are grounded in Chinese-language human-AI dialogue. An English-calibrated version doesn't exist yet.

**Install**:
```bash
cp multi-dimensional-collaboration-protocol.md ~/.claude/skills/
```
Claude Code loads it automatically each session. No manual invocation needed.

---

## 它解决什么问题

AI 在单维度优化上可以超越人类——逻辑推理、代码生成、模式匹配。但 AI 在结构上缺失三个维度：感知不到时间成本，判断不了目标是否值得，看不到自己是否被锁在一条思维路径上。

这个协议做两件事：

1. **给人类一个理解 AI 的框架**——知道 AI 哪里强、哪里在结构上有盲区，然后自然地用对应的方式通信（给症状不给诊断、用自然语言画架构、用标签激活知识分布、用精度变化传递信任信号）
2. **给 AI 一套可执行的规则**——11 条从框架推导出的行为模式，大部分通过信号识别即可执行，不需要元认知

---

## 快速开始

```bash
# 安装到个人目录（推荐，每个 session 自动加载）
cp multi-dimensional-collaboration-protocol.md ~/.claude/skills/

# 或安装到项目
cp multi-dimensional-collaboration-protocol.md your-project/.claude/skills/
```

不需要手动调用。安装后 AI 在每个 session 中使用这套框架。

---

## 协议结构

| 节 | 内容 |
|----|------|
| §1 你的认知架构 | AI 能做什么、在结构上做不了什么——诚实的自我认知 |
| §2 人类如何补偿 | 人类充当 AI 缺失的三个维度：时间代理、价值代理、元认知代理 |
| §3 人类的通信编码 | 观察-诊断分离、知识边界标记、自然语言画架构、标签激活、注意力锚定、精度作为信号 |
| §4 用框架引导自己 | AI 如何用结构化检查点补偿自己没有元认知的局限 |
| §5 执行规则 | 11 条可执行的行为模式——触发条件、行动序列、推导来源 |
| §6 共享词汇 | 框架的核心概念：单维度锁定、紧反馈循环、验收标准错位、维度切换信号、错误的精确 |
| §7 对话的五个平面 | 元对话、架构、规格、纠正、执行——识别平面，匹配行为 |

---

## 适合谁

- 与 AI 进行复杂工程协作，发现 AI 有时很好有时犯傻但说不清为什么
- 想从原理层面理解 AI 的行为模式，而非背 prompt 模板
- 想建立可迭代、可修改的 AI 协作方法论

## 不适合谁

- 偶尔让 AI 写小脚本——不需要一个协作协议
- 只想要「最佳 prompt 合集」——这个项目给的是原理和规则，不是模板

---

## 验证范围

- 在 Claude Code + DeepSeek V4-Pro 环境下提炼和测试
- 原理层（§1-§4）应具有跨模型通用性
- 具体行为规则（§5）在其他模型下可能需要调整

---

## 许可

MIT
