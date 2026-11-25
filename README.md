# 论证拆解与论证批判

[English](#english)

这两个 Codex skill 最初是给我自己用的。现在放出来，方便有同样需求的人做个人学习和非商业研究。

- [论证拆解](argument-decomposition/SKILL.md) 从原文重构前提、结论及推理关系，标出隐含前提和支持缺口。
- [论证批判](argument-criticism/SKILL.md) 在拆解的基础上检验推理、前提和结构，判断各条路线能给结论多少支持。

把两个目录并列放进 Codex 的个人技能目录 `~/.codex/skills/`，保留各自的 `references/` 和 `agents/`。可以分别用 `$argument-decomposition` 和 `$argument-criticism` 调用。报告默认跟随提问语言。英文提问使用英文标题和术语，中文报告中的技术标签采用「中文（English）」格式。明确指定输出语言时，以指定语言为准。

## 关于 AI 制作

这两个 skill 由 ChatGPT 辅助设计，并主要由 ChatGPT 制作。如果你介意使用 AI 制作的内容，可以选择不使用。

## 自用与免责

这套 skill 按现状提供。我不保证分析结果正确、完整或可靠。请自行核对原文、证据和推理，并自行承担使用和据此作出判断的风险。在适用法律允许的范围内，我不对因使用本项目或其输出而产生的损失承担责任。觉得这套做法不适合你，欢迎自己写一套。

## 更新计划

接下来计划更新并分享以下三个项目。发布时间未定。

- **完整论证创作工作流**（`complete-argument-creation`）将问题拆解、论证链接、论证拆解和论证批判串起来。它从指定问题和结论出发构造论证，并根据检验结果修订。
- **问题拆解**（`problem-decomposition`）澄清问题的范围、关键术语和回答条件，识别会改变答案或证据要求的子问题。
- **论证链接**（`argument-linking`）为指定结论构造论证，寻找支持该结论的理由，并保留结论原有的强度。

## 许可证

本项目采用 [PolyForm Strict License 1.0.0](LICENSE)。许可证允许个人学习等非商业用途，未授予商用、修改或重新分发的许可。完整条款以英文许可证为准。GitHub 站内的查看和 fork 权限适用 [GitHub 服务条款](https://docs.github.com/en/site-policy/github-terms/github-terms-of-service#5-license-grant-to-other-users)。

Copyright © 2026 mangguoMC

## English

### Argument Decomposition and Argument Criticism

I originally made these two Codex skills for my own use. I’m sharing them for personal study and noncommercial research.

- [Argument Decomposition](argument-decomposition/SKILL.md) reconstructs the premises, conclusions, and inferential relationships in a source. It identifies implicit premises and gaps in support.
- [Argument Criticism](argument-criticism/SKILL.md) uses that reconstruction to evaluate the inferences, premises, and structure of the argument. It assesses how much support each line of reasoning gives the conclusion.

Place both directories side by side in your personal Codex skills directory, `~/.codex/skills/`, keeping the `references/` and `agents/` folders in each. Invoke them with `$argument-decomposition` and `$argument-criticism`. Reports default to the language of your request. English reports use English headings and terminology. Chinese reports give technical labels in Chinese with the English term in parentheses. You can also specify the output language explicitly.

### AI involvement

ChatGPT assisted with the design and did most of the work of creating these skills. If you prefer not to use AI-produced material, feel free to skip them.

### Personal use and disclaimer

These skills are provided as is. I make no guarantees about the accuracy, completeness, or reliability of their results. Verify the source text, evidence, and reasoning for yourself. You use the skills and act on their results at your own risk. To the extent permitted by applicable law, I accept no liability for losses arising from use of this project or its output. If this approach doesn’t suit you, feel free to build your own.

### License

This project uses the [PolyForm Strict License 1.0.0](LICENSE). The license permits noncommercial uses such as personal study and grants no permission for commercial use, modification, or redistribution. See the license for the full terms. Viewing and forking on GitHub are governed by the [GitHub Terms of Service](https://docs.github.com/en/site-policy/github-terms/github-terms-of-service#5-license-grant-to-other-users).

### Roadmap

I plan to update and share the following. There is no release date yet.

- **Complete Argument Creation workflow** (`complete-argument-creation`) brings problem decomposition, argument linking, argument decomposition, and argument criticism into one workflow. It builds an argument from a specified question and conclusion, then revises it based on the review.
- **Problem Decomposition** (`problem-decomposition`) clarifies a question’s scope, key terms, and conditions for answering it. It identifies subquestions that could change the answer or the evidence required.
- **Argument Linking** (`argument-linking`) builds an argument for a specified conclusion. It seeks reasons that support the conclusion while preserving its original strength.
