# GitHub 活跃与维护计划 | GitHub Activity & Maintenance Plan

目标不是为了贡献图制造无意义提交，而是持续交付可复用的一人工作流与 Codex Skills。  
The goal is not to manufacture activity, but to continuously ship useful solo workflows and reusable Codex Skills.

## 一、目标 | Goals

- 每周保持 2–4 天真实、有意义的开发活动。
- 每月至少完成一个可展示的里程碑：新 Skill、功能升级、文档完善或正式版本。
- 所有仓库保持中英双语、状态清晰、可复用、无敏感数据。
- 优先维护少量高质量仓库，避免同时启动过多空项目。

- Maintain 2–4 days of genuine development activity each week.
- Complete at least one visible milestone each month: a new Skill, feature update, documentation improvement, or release.
- Keep every repository bilingual, clearly labeled, reusable, and free of sensitive data.
- Prioritize a small number of quality repositories instead of creating many empty projects.

## 二、每周节奏 | Weekly cadence

### 周一：规划 / Monday — Plan

- 回顾 Issues 和上周进度。
- 为本周选择一个明确交付物。
- 新建或更新一个 Issue，写明目标、完成标准和边界。

- Review issues and last week's progress.
- Choose one concrete weekly deliverable.
- Create or update an issue with goals, completion criteria, and scope.

### 周二至周四：开发 / Tuesday–Thursday — Build

- 在独立分支开发一个小功能或 Skill。
- 每次提交只解决一个清晰问题，使用可读的提交信息。
- 同步更新中英双语 README、示例和安全说明。
- 有条件时通过 Pull Request 合并，保留清晰的变更记录。

- Build one small feature or Skill on a focused branch.
- Keep each commit scoped to one clear change with a readable message.
- Update bilingual README content, examples, and safety notes.
- Merge through a pull request when useful to preserve a clear change history.

### 周五：验证与总结 / Friday — Verify and summarize

- 测试主要使用路径。
- 检查是否包含密钥、密码、个人敏感数据或无关文件。
- 更新 Issue、CHANGELOG 或 README 中的进度。
- 合并已完成的改动。

- Test the main usage path.
- Check for secrets, passwords, sensitive data, and unrelated files.
- Update the issue, changelog, or README with progress.
- Merge completed work.

### 周末：轻维护 / Weekend — Light maintenance

- 回复 Issues 和反馈。
- 修正小型文档问题。
- 记录下周想法，不为了活跃度强行提交。

- Respond to issues and feedback.
- Fix small documentation problems.
- Capture ideas for next week without forcing commits for activity.

## 三、每月节奏 | Monthly cadence

### 第 1 周：选择主题 / Week 1 — Select a theme

确定本月重点，例如金融数据工作流、区块链工具、Codex 自动化或内容处理。

Choose one monthly theme, such as financial-data workflows, blockchain tools, Codex automation, or content processing.

### 第 2–3 周：实现与测试 / Weeks 2–3 — Build and test

- 完成核心流程。
- 加入中英双语说明和最小可运行示例。
- 为 Skill 测试直接触发、间接触发、不完整输入、不应触发和边界情况。

- Complete the core workflow.
- Add bilingual documentation and a minimal runnable example.
- Test direct triggers, indirect triggers, incomplete inputs, non-trigger cases, and edge cases.

### 第 4 周：发布 / Week 4 — Release

- 更新 `CHANGELOG.md`。
- 使用语义版本，如 `v0.1.0`、`v0.2.0`、`v1.0.0`。
- 创建 GitHub Release，提供中英双语发布说明。
- 在个人主页的项目列表中加入已成熟的 Skill。

- Update `CHANGELOG.md`.
- Use semantic versions such as `v0.1.0`, `v0.2.0`, and `v1.0.0`.
- Create a GitHub Release with bilingual release notes.
- Add mature Skills to the profile project list.

## 四、每季度维护 | Quarterly maintenance

每三个月检查一次：

- 哪些仓库仍在维护，哪些应标记为规划中、维护中或已归档。
- README、链接、示例和联系方式是否仍然有效。
- 依赖、脚本和安全说明是否过期。
- 是否存在长期空仓库或重复项目。
- 精选仓库是否仍代表当前方向。
- 是否需要合并、拆分或归档 Skill。

Every three months, review:

- Which repositories are active, planned, maintained, or archived.
- Whether README files, links, examples, and contact details still work.
- Whether dependencies, scripts, and security notes are current.
- Whether empty or duplicated repositories remain.
- Whether pinned repositories still represent the current focus.
- Whether Skills should be merged, split, or archived.

## 五、每个 Skill 的完成标准 | Definition of done for each Skill

- [ ] 有清晰、聚焦的用户目标 / A clear, focused user goal
- [ ] `SKILL.md` 包含有效的 `name` 与 `description`
- [ ] 说明触发条件、输入、步骤、输出、边界和停止条件
- [ ] 提供中英双语 README
- [ ] 有最小示例和测试记录
- [ ] 不包含密钥、令牌、密码或个人敏感数据
- [ ] 有版本号和变更记录
- [ ] 选择合适的 License
- [ ] 发布 GitHub Release（达到可复用阶段时）

- [ ] `SKILL.md` contains valid `name` and `description`
- [ ] Triggers, inputs, steps, outputs, boundaries, and stop conditions are defined
- [ ] A bilingual README is included
- [ ] Minimal examples and test notes are provided
- [ ] No keys, tokens, passwords, or sensitive personal data
- [ ] Version and changelog are present
- [ ] An appropriate license is selected
- [ ] A GitHub Release is published when the Skill becomes reusable

## 六、当前仓库优先级 | Current repository priorities

1. **个人主页 / Profile**：持续维护项目索引和最新方向。
2. **未来的 Skills 仓库 / Future Skills repositories**：主要开发重点。
3. **whisper-contract**：补测试、部署记录和版本发布。
4. **whisper-viewer**：有可运行原型后再进入 Active 状态。
5. **My-Life-as-a-Human-Like-Being**：完成个人化前保持 Planning 状态。

## 七、贡献记录注意事项 | Contribution notes

- 使用与 GitHub 账号关联的提交邮箱。
- 工作完成后合并到默认分支。
- Fork 仓库中的普通提交通常不会计入个人贡献图；更适合通过 Pull Request 回馈上游。
- Issue、Pull Request、Review 和 Discussion 也属于有意义的维护活动。

- Use a commit email connected to the GitHub account.
- Merge completed work into the default branch.
- Ordinary commits in a fork generally do not appear on the personal contribution graph; contribute upstream through pull requests when appropriate.
- Issues, pull requests, reviews, and discussions are also meaningful maintenance activities.

## 参考 | References

- [GitHub profile contributions](https://docs.github.com/en/account-and-profile/reference/profile-contributions-reference)
- [GitHub releases](https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases)
- [GitHub issue and pull request templates](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/about-issue-and-pull-request-templates)
- [OpenAI — Build skills](https://developers.openai.com/plugins/build/skills)
