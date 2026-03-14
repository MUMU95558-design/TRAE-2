# TRAE-2

我的 Claude Skills 集合，用于提升 AI 辅助开发效率。

## 📦 包含的 Skills

### vibe-prd-writer

帮 AI PM 快速写出可以直接喂给 AI 执行的一页纸 PRD。

**适用场景：**
- 当你说"帮我写个PRD"
- 当你说"我想做一个XX"
- 当你说"帮我梳理需求"
- 当你提到产品构思、功能规划、原型开发

**核心特性：**
- 10 分钟内把模糊想法变成可执行的 PRD
- 5 个必问问题引导需求澄清
- 自动推荐技术方案
- 生成 AI 可直接执行的指令
- 内置质量自检清单

**工作流程：**
1. 判断用户状态（想法模糊 vs 需求清晰）
2. 需求澄清（为什么、给谁用、核心功能、不做什么、成功标准）
3. 技术方案建议（根据产品类型自动推荐）
4. 生成一页纸 PRD
5. 质量自检

### skill-creator

官方 Anthropic skill-creator，用于创建、测试和优化 Claude Skills。

**核心功能：**
- 交互式 skill 创建向导
- 自动生成 SKILL.md 模板
- 内置评估系统
- 迭代优化工作流

## 🚀 如何使用

### 安装 Skills

1. 克隆这个仓库：
```bash
git clone https://github.com/MUMU95558-design/TRAE-2.git
cd TRAE-2
```

2. 将 skills 复制到你的 Claude 项目：
```bash
cp -r .trae/skills/* /path/to/your/project/.trae/skills/
```

### 使用 vibe-prd-writer

在 Claude Code 或 Cursor 中，直接说：

```
帮我写个PRD，我想做一个记账 app
```

或者：

```
我要 vibe code 一个产品，帮我梳理需求
```

AI 会自动引导你完成需求澄清，并生成可执行的 PRD。

### 使用 skill-creator

在 Claude Code 中，说：

```
帮我创建一个新的 skill
```

AI 会引导你完成 skill 的创建、测试和优化。

## 📝 Skill 结构

每个 skill 都包含一个 `SKILL.md` 文件，格式如下：

```markdown
---
name: "skill-name"
description: "简短描述，说明何时触发这个 skill"
---

# Skill 名称

详细的 skill 说明和使用指南...
```

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📄 License

MIT License