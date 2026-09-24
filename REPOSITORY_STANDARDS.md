# 仓库规范 | Repository Standards

这份规范用于今后发布的一人工作流、Codex Skills 和其他项目。  
This standard applies to future solo workflows, Codex Skills, and other projects.

## 1. 中英双语 | Bilingual by default

- README 先中文、后英文，并提供页内语言导航。
- 仓库简介同时包含中英文关键词。
- 安装、用法、限制和安全提示必须双语。
- Use Chinese first and English second, with language links.
- Keep setup, usage, limitations, and safety notes bilingual.

## 2. README 基本结构 | README structure

1. 项目简介 / Overview
2. 状态 / Status
3. 功能 / Features
4. 快速开始 / Quick start
5. 目录结构 / Structure
6. 限制与安全 / Limitations & security
7. 许可证 / License
8. 联系方式 / Contact

## 3. 项目状态 | Project status

统一使用以下状态：  
Use one of these status labels:

- `Planning / 规划中`
- `Active / 持续开发`
- `Maintenance / 维护中`
- `Archived / 已归档`

## 4. Codex Skill 结构 | Codex Skill structure

每个 Skill 使用独立目录，并至少包含 `SKILL.md`。详细材料按需拆分：  
Each Skill uses its own directory and includes at least `SKILL.md`. Add supporting folders only when needed:

```text
skill-name/
├── SKILL.md
├── references/   # 可选：说明、规范、示例 / optional docs and examples
├── scripts/      # 可选：确定性脚本 / optional deterministic scripts
└── assets/       # 可选：模板与素材 / optional templates and assets
```

`SKILL.md` 必须包含 YAML front matter 中的 `name` 和 `description`，正文应说明触发条件、输入、步骤、输出、边界和停止条件。  
`SKILL.md` must include `name` and `description` in YAML front matter. Its body should define triggers, inputs, steps, outputs, boundaries, and stop conditions.

参考 / Reference: [OpenAI — Build skills](https://developers.openai.com/plugins/build/skills)

## 5. 发布检查 | Release checklist

- [ ] README 中英双语 / bilingual README
- [ ] 清晰的状态与用途 / clear status and purpose
- [ ] 可运行或可复用示例 / runnable or reusable example
- [ ] 限制与安全提示 / limitations and safety notes
- [ ] 合适的 License / appropriate license
- [ ] 无密钥、密码或个人敏感数据 / no secrets, passwords, or sensitive data
