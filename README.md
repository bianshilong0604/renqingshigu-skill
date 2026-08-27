# 个人社会化应对 Skill

这是一个面向真实社交场景的中文 Codex Skill。用户提供结构化背景后，它根据规则和实战案例生成自然、可直接使用、能够应对追问的回复。

## 包含内容

- `SKILL.md`：Skill 主入口与调用契约
- `references/可执行规则库_Rules_v1.2.1-social-flow.md`：G01–G13、R-L01–R-L78
- `references/规范化知识地图.md`：78 课规范化地图
- `references/实战案例路由索引.md`：199 个案例/示范单元
- `references/具体理由模板库.md`：低风险具体理由候选
- `知识卡片/`：89 个 Markdown 知识卡片
- `tests/`：三轮规则级回归测试报告

## 安装

将整个 `personal-social-coach` 文件夹复制到 Codex 的 skills 目录，例如：

```text
~/.codex/skills/personal-social-coach/
```

然后在新任务中使用 `$personal-social-coach`，或让 Codex 根据描述自动调用。

## 推荐输入

```text
场景与当前任务：
对方关系与权力差：
对方原话或可观察行为：
我的真实目标：
时间、精力与资源约束：
安全风险：
```

不需要每次填满；只有缺失信息会改变结论时才追问。

## 数据边界

本 GitHub 版本只包含用于 Skill 运行的 Markdown 知识内容。原知识库中的 `实践记录/`、`.obsidian/` 和 `原材料/` 未纳入：前两者属于个人运行数据或本机配置，后者为非运行时 PDF 原材料。

如果仓库公开发布，请先确认这些用户自有知识卡片适合公开；默认建议使用私有仓库。
