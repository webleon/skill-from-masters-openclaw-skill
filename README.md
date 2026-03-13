# Skill from Masters - OpenClaw Skill

从大师学习 - 完整的 skill 创建系统。整合方法论搜索、GitHub 学习、文档提取、创建助手四大功能。

---

## 📋 功能概览

| 功能 | 说明 |
|------|------|
| **专家方法论搜索** | 搜索 6 大领域专家方法论（写作、产品、技术、销售、决策等） |
| **从 GitHub 学习** | 深入分析 GitHub 项目，提取核心知识 |
| **从文档提取** | 从文档/示例反向工程方法论 |
| **Skill 创建助手** | 提供模板、质量检查、最佳实践 |

---

## 🚀 安装

```bash
git clone https://github.com/webleon/skill-from-masters-openclaw-skill.git ~/.openclaw/workspace/skills/skill-from-masters-openclaw-skill
```

---

## 📖 使用示例

### 示例 1: 创建代码审查 skill

```
用户："我想创建一个代码审查 skill"

skill-from-masters-openclaw-skill：
> 让我帮你创建一个高质量的代码审查 skill。
>
> 我找到了几位权威专家的方法论：
> - Martin Fowler：Refactoring 作者，提倡小步重构
> - Robert Martin：Clean Code 作者，强调可读性
> - Google：官方代码审查指南
>
> 基于这些方法论，我创建 code-review skill，包含：
> 1. Google 的检查清单
> 2. Fowler 的重构建议
> 3. 建设性反馈模板
```

### 示例 2: 从 GitHub 项目学习

```
用户："从 ascii-image-converter 学习创建 skill"

skill-from-masters-openclaw-skill：
> 让我分析 ascii-image-converter 项目...
>
> 核心方法：
> 1. 亮度计算公式
> 2. 宽高比处理
> 3. 字符集映射方法
```

### 示例 3: 从文档提取方法论

```
用户："从这篇文章提取写作方法论"

skill-from-masters-openclaw-skill：
> 让我分析这篇文章...
>
> 提取的方法论：
> 1. Pyramid Principle（结论先行）
> 2. MECE 原则
> 3. 自顶向下结构
```

---

## 📚 专家数据库

### 写作与沟通
- Barbara Minto - Pyramid Principle
- William Zinsser - On Writing Well
- Amazon - 6-Pager

### 产品管理
- Marty Cagan - Inspired
- Teresa Torres - Continuous Discovery
- Gibson Biddle - DHM Model

### 用户研究
- Rob Fitzpatrick - The Mom Test
- Steve Portigal - Interviewing Users
- JTBD - Jobs to Be Done

### 工程技术
- Martin Fowler - Refactoring
- Robert Martin - Clean Code
- Google - Code Review

### 销售与谈判
- Chris Voss - Never Split
- Neil Rackham - SPIN Selling

### 决策与思维
- Charlie Munger - Mental Models
- Jeff Bezos - Decision Making

---

## ✅ 质量标准

在创建 skill 前验证：
- [ ] 搜索了专家方法论（如有）
- [ ] 深入分析了参考项目/文档
- [ ] 使用了合适的模板
- [ ] 步骤具体可执行
- [ ] 有质量检查点
- [ ] 有常见陷阱和避免方法

---

## 📝 技能模板

```markdown
---
name: {skill-name}
description: {一句话描述}
model: qwen3.5-plus
---

# {Skill Name}

{一句话描述}

---

## 触发条件
| 场景 | 示例 |
|------|------|
| {场景 1} | "{示例 1}" |

---

## 工作流程
### Step 1: {步骤名}
[做什么]

---

## 质量标准
- [ ] [检查点 1]
- [ ] [检查点 2]
```

---

## ⚠️ 注意事项

1. **质量优先** - 不创建低质量 skill
2. **具体化** - 避免抽象原则
3. **示例驱动** - 提供好的示例
4. **可验证** - 质量检查点可验证
5. **迭代改进** - 鼓励反馈和迭代

---

## 🔗 相关资源

- [OpenClaw 文档](https://docs.openclaw.ai)
- [OpenClaw GitHub](https://github.com/openclaw/openclaw)

---

## 📄 许可证

MIT License
