# competitor-analysis

一个 Codex 技能：竞品分析引擎。对比或对标竞品、分析市场定位、评估产品差异、制定功能 / 定价 / 市场进入策略时使用，产出聚焦"差距、机会、可执行建议"的结构化报告。

## 安装

方式一：直接复制。把 `competitor-analysis/` 目录放进本机 `~/.codex/skills/` 下，新开会话即可用。

方式二：用 Codex 内置的 skill-installer 从本仓库安装：

```bash
install-skill-from-github.py --repo <owner>/competitor-analysis --path competitor-analysis
```

或直接对 Codex 说"用 skill-installer 安装 <owner>/competitor-analysis 里的 competitor-analysis"。

## 结构

```text
competitor-analysis/
├── SKILL.md                     核心流程与决策规则
├── agents/openai.yaml           UI 元信息
├── references/
│   ├── frameworks.md            6 个分析框架及适用场景
│   └── info-sources.md          信息收集与可信度规范
└── assets/
    └── report-template.md       报告输出模板
```

## License

MIT，见仓库根目录 [LICENSE](LICENSE)。

