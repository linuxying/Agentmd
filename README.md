# Agentmd

减少 LLM 编码常见错误的行为准则（AGENTS.md），提供中英双语版本。

Behavioral guidelines to reduce common LLM coding mistakes, available in English and Chinese.

## 文件说明 / Files

| 文件 / File | 语言 / Language | 说明 / Description |
|---|---|---|
| [AGENTS.md](AGENTS.md) | English | 英文版行为准则 |
| [AGENTS-zh.md](AGENTS-zh.md) | 中文 | 中文版行为准则 |

## 核心原则 / Core Principles

1. **先思考，再编码 / Think Before Coding** — 明确假设，列出多种解释，不静默选择。
2. **简单优先 / Simplicity First** — 用最少代码解决问题，不做投机性设计。
3. **外科手术式修改 / Surgical Changes** — 只改必须改的，不重构没坏的东西。
4. **目标驱动执行 / Goal-Driven Execution** — 定义可验证的成功标准，循环直到通过。
5. **验证与证据 / Verification & Evidence** — 完成前先验证，不伪造结果。
6. **安全与依赖 / Safety & Dependencies** — 破坏性操作前先确认，优先可回滚方案。
7. **提问与交付格式 / Asking & Delivery Format** — 阻塞时结构化提问，交付时说明验证情况。

## 用法 / Usage

将 `AGENTS.md`（或中文版 `AGENTS-zh.md`）放在项目根目录，作为 AI 编码助手的行为指引。可按需与项目特定指令合并，项目规则优先于通用准则。

Place `AGENTS.md` (or the Chinese version `AGENTS-zh.md`) in your project root as behavioral guidelines for AI coding agents. Merge with project-specific instructions as needed; project rules take precedence.

## License

MIT
