# Skill from Masters - OpenClaw Skill

从大师学习 - 完整的 skill 创建系统。整合方法论搜索、GitHub 学习、文档提取、创建助手四大功能。

**核心理念：** 站在巨人的肩膀上 - 基于经过验证的专家方法论创建 skill。

---

## 📋 功能概览

| 功能 | 说明 |
|------|------|
| **专家方法论搜索** | 搜索 6 大领域专家方法论（写作、产品、技术、销售、决策等） |
| **从 GitHub 学习** | 深入分析 GitHub 项目，提取核心知识 |
| **从文档提取** | 从文档/示例反向工程方法论 |
| **Skill 创建助手** | 提供模板、质量检查、最佳实践 |

---

## 🚀 快速开始

### 安装

```bash
git clone https://github.com/webleon/skill-from-masters-openclaw-skill.git ~/.openclaw/workspace/skills/skill-from-masters-openclaw-skill
```

### 使用

在 OpenClaw 中直接调用：

```
我想创建一个代码审查 skill
```

---

## 📖 完整使用指南

### 方式 1：专家方法论搜索

**适用场景：** 创建新 skill 时，想基于专家方法论

**触发词：**
- "我想创建一个...skill"
- "帮我创建...skill"
- "如何创建...skill"

**示例：**

```
用户："我想创建一个代码审查 skill"

skill-from-masters：
> 让我帮你创建一个高质量的代码审查 skill。
>
> ## Step 1: 搜索专家方法论
>
> 我找到了几位权威专家的方法论：
>
> **工程技术领域：**
> - **Martin Fowler**：Refactoring 作者，提倡小步重构
> - **Robert Martin**：Clean Code 作者，强调可读性
> - **Google**：官方代码审查指南
>
> **核心原则共识：**
> 1. 代码可读性优先
> 2. 小批量审查（<400 行）
> 3. 建设性反馈
>
> ## Step 2: 选择模板
>
> 推荐使用 **How-to + Checklist** 模板。
>
> ## Step 3: 创建 Skill
>
> 基于这些方法论，我创建 code-review skill，包含：
> 1. Google 的检查清单
> 2. Fowler 的重构建议
> 3. 建设性反馈模板
>
> 这样可以吗？
```

---

### 方式 2：从 GitHub 项目学习

**适用场景：** 有特定的 GitHub 项目想学习方法论

**触发词：**
- "从...学习"
- "学习...项目"
- "分析...GitHub 项目"

**示例：**

```
用户："从 ascii-image-converter 学习创建 skill"

skill-from-masters：
> 让我分析 ascii-image-converter 项目...
>
> ## 深入分析
>
> 我分析了这个项目，提取了核心知识：
> 1. 亮度计算公式
> 2. 宽高比处理
> 3. 字符集映射方法
>
> 要我创建 ascii-art-converter skill 吗？
```

**工作流程：**
1. 搜索 GitHub 项目（stars>100，活跃维护）
2. 展示候选项目（前 3-5 个）
3. **等待用户确认**后深入分析
4. 阅读 README、源码、示例
5. 提取核心方法论
6. 创建 skill

---

### 方式 3：从文档提取方法论

**适用场景：** 有文档、文章或示例想提取方法论

**触发词：**
- "从...提取"
- "分析这篇文章"
- "学习这个文档"

**示例：**

```
用户："从这篇文章提取写作方法论"

skill-from-masters：
> 让我分析这篇文章...
>
> 提取的方法论：
> 1. Pyramid Principle（结论先行）
> 2. MECE 原则
> 3. 自顶向下结构
>
> 要我创建 technical-writing skill 吗？
```

**两条路径：**

#### 路径 A：方法论文档
- 有"如何"、"步骤"、"指南"等词
- 验证适用性（至少满足 2 项）
  - [ ] 有清晰目标
  - [ ] 有可重复步骤
  - [ ] 有质量标准
  - [ ] 有场景描述

#### 路径 B：反向工程示例
- 是完成的作品（文章、设计、代码）
- 分析结构、提取质量特征
- 反向工程流程

---

### 方式 4：Skill 创建助手

**适用场景：** 需要 skill 模板或质量检查

**触发词：**
- "检查 skill 质量"
- "skill 模板"
- "如何改进 skill"

**示例：**

```
用户："帮我检查这个 skill 的质量"

skill-from-masters：
> 让我检查你的 skill...
>
> ## 质量检查
>
> ✅ 有 name 和 description
> ✅ 有触发条件表格
> ✅ 有工作流程
> ❌ 缺少质量标准
>
> 建议添加质量检查点。
```

---

## 🎯 完整工作流程

```
用户请求
    │
    ├─ 需要方法论？
    │   └─ YES → 搜索专家方法论（方式 1）
    │
    ├─ 从 GitHub 学习？
    │   └─ YES → 深入分析项目（方式 2）
    │
    ├─ 从文档提取？
    │   └─ YES → 提取方法论（方式 3）
    │
    └─ 创建/检查 skill
        └─ 使用模板 + 质量检查（方式 4）
```

---

## 📚 6 大专家领域

### 1. 写作与沟通
| 专家 | 方法论 | 核心原则 |
|------|--------|---------|
| Barbara Minto | Pyramid Principle | 结论先行、MECE |
| William Zinsser | On Writing Well | 简洁、清晰 |
| Amazon | 6-Pager | 叙事体、逆向工作 |

### 2. 产品管理
| 专家 | 方法论 | 核心原则 |
|------|--------|---------|
| Marty Cagan | Inspired | 问题优先、结果导向 |
| Teresa Torres | Continuous Discovery | 每周访谈 |
| Gibson Biddle | DHM Model | Delight、Hard-to-copy、Margin |

### 3. 用户研究
| 专家 | 方法论 | 核心原则 |
|------|--------|---------|
| Rob Fitzpatrick | The Mom Test | 不问观点问事实 |
| Steve Portigal | Interviewing Users | 深度倾听 |
| JTBD | Jobs to Be Done | 用户雇佣产品做什么 |

### 4. 工程技术
| 专家 | 方法论 | 核心原则 |
|------|--------|---------|
| Martin Fowler | Refactoring | 小步重构 |
| Robert Martin | Clean Code | 可读性、单一职责 |
| Google | Code Review | 可读性优先 |

### 5. 销售与谈判
| 专家 | 方法论 | 核心原则 |
|------|--------|---------|
| Chris Voss | Never Split | 战术同理心 |
| Neil Rackham | SPIN Selling | 情境、问题、暗示、需求 |

### 6. 决策与思维
| 专家 | 方法论 | 核心原则 |
|------|--------|---------|
| Charlie Munger | Mental Models | 多元思维 |
| Jeff Bezos | Decision Making | 单向门/双向门 |

---

## ✅ 质量检查清单

在创建 skill 前验证：
- [ ] 搜索了专家方法论（如有）
- [ ] 深入分析了参考项目/文档
- [ ] 使用了合适的模板
- [ ] 步骤具体可执行
- [ ] 有质量检查点
- [ ] 有常见陷阱和避免方法

---

## 📝 Skill 模板

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
- [Skill from Masters GitHub](https://github.com/webleon/skill-from-masters-openclaw-skill)

---

## 📄 许可证

MIT License
