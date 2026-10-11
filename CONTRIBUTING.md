# Contributing

Thanks for keeping this list sharp. 谢谢帮助维护本列表。中文说明在下半部分。

## The bar for an entry

1. **Primary sources only.** Link the arXiv abs page or the official repo. No aggregators, no tweets, no secondhand summaries.
2. **State what it automates.** One line on the concrete loop being automated: data cleaning / evaluation / synthesis, training runs, hyperparameter search, distillation, post-training.
3. **Respect the product boundary.** The deliverable must be a **model or a dataset**:
   - Agent improves code that tests verify → [awesome-self-improving-coding-agents](https://github.com/vicfei/awesome-self-improving-coding-agents)
   - Agent changes how an organization works (skills, memory, permissions) → [awesome-ai-native](https://github.com/vicfei/awesome-ai-native)
   - Classic MLOps (deploy/monitor) and pre-agent AutoML papers (NAS era) → the incumbents in the related-lists section
4. **Flag licenses.** If a system ships a non-OSI license (source-available / NOASSERTION), say so in the row.

## Checklist for PRs

- [ ] Added to the right section in **both** `README.md` and `README.zh-CN.md` (keep the two in sync).
- [ ] Link resolves (no 404) — yes, please actually click it.
- [ ] "What it automates" stated concretely.
- [ ] One-line description, English in `README.md`, 中文在 `README.zh-CN.md`。

Keyword tuning for the [radar](scripts/radar.py) is also welcome — keep precision high (broad terms like "synthetic data" or "self-training" flood the filter; they are deliberately excluded).

## 贡献指南（中文）

**收录门槛：**

1. **只链一手来源**——arXiv 页面或官方仓库；不收聚合站、推特转述或二手总结。
2. **说明自动化了什么**——一句话讲清被自动化的具体回路：数据清洗/评测/合成、训练运行、超参搜索、蒸馏、后训练。
3. **遵守产品分界。** 交付物必须是**模型或数据集**：
   - agent 改进可被测试验证的代码 → [awesome-self-improving-coding-agents](https://github.com/vicfei/awesome-self-improving-coding-agents)
   - agent 改变组织运转方式（技能、记忆、权限）→ [awesome-ai-native](https://github.com/vicfei/awesome-ai-native)
   - 经典 MLOps（部署/监控）与 agent 时代之前的 AutoML 论文 → 相邻列表中的在位者
4. **标注许可证。** 若系统采用非 OSI 许可（source-available / NOASSERTION），请在条目中注明。

**PR 检查项：** 中英两个 README 同步更新；链接实际点开过；"自动化了什么"说得具体；一句话描述中英各一份。也欢迎调整[雷达](scripts/radar.py)关键词——保持高精度（"synthetic data"、"self-training" 这类宽词会淹没过滤器，已被刻意排除）。
