# index.md - 项目总览、知识库导航

---

## 1. 项目简介

**ExprBuild-Julia** 是一个面向 Desmos 图形计算器表达式编程与管理的实验性框架，当前处于需求探索与原型验证阶段。  
本知识库采用“页面即目录”结构，每个 index.md 既是本层级的导航，也是本层级知识的入口和父文档。

---

## 2. 目录结构与文档导航

> **如何使用本知识库？**  
> - 任何AI助手或新成员，**第一步只需阅读本index.md**。  
> - 阅读后请根据“任务类型”与“导航指引”自主决策下一步要查阅的子文档或子目录。

### 2.1 顶层目录

| 名称/路径                | 类型     | 简要说明                         | 适用任务/关键词           |
|--------------------------|----------|----------------------------------|---------------------------|
| 项目介绍 v0.3.md         | 文档     | 项目目标、愿景、核心设计         | 全局理解、背景、架构       |
| 开始指南.md              | 文档     | 项目结构、开发流程、入门指引     | 新手入门、开发环境         |
| 术语表.md                | 文档     | 关键术语定义与区分               | 术语、定义、歧义消除       |
| 对象模型设计.md          | 文档     | ExprBuild对象系统详细设计        | 架构、对象、数据结构       |
| 依赖管理.md              | 文档     | 依赖追踪与冲突检测机制           | 依赖、引用、冲突           |
| 任务历史.md              | 文档     | 记录AI协作任务、输入输出、结论   | 复盘、历史、溯源           |
| AI协作守则.md            | 文档     | AI助手行为规范与自查流程         | 协作规范、行为约束         |
| core/                    | 目录     | 核心表达式系统源码及子文档       | 代码实现、表达式处理       |
| examples/                | 目录     | 示例代码与用例                   | 示例、测试、用法           |
| test/                    | 目录     | 测试用例                         | 测试、验证                 |
| working-notes/           | 目录     | 工作笔记、设计文档、子知识库     | 设计、探索、细分主题       |

> **说明**：每个子目录下均有自己的 index.md，作为该层级的导航与父文档。

---

## 3. AI助手协作指引

### 3.1 必读原则

- **所有AI助手/新成员，第一步必须阅读本index.md。**
- 阅读后请根据任务类型、关键词、导航表，自主决策下一步要查阅的文档或目录。

### 3.2 决策建议

- **术语/定义相关**：优先查阅 `术语表.md`
- **架构/对象设计相关**：查阅 `对象模型设计.md`、`依赖管理.md`
- **开发/实现相关**：查阅 `开始指南.md`、`core/` 目录
- **历史/复盘相关**：查阅 `任务历史.md`
- **协作规范相关**：查阅 `AI协作守则.md`
- **具体主题/细分领域**：进入 `working-notes/` 或其他子目录，优先阅读其 index.md
- **不确定时**：优先查阅 `项目介绍 v0.3.md` 和本 index.md

### 3.3 行为建议

- **自查**：如遇信息不全、歧义、上下文缺失，优先查阅相关文档，不要直接向用户提问。
- **最小必要原则**：只查阅与当前任务直接相关的文档，避免信息过载。
- **知识沉淀**：任务完成后，将关键结论、决策、代码片段等补充到相关文档或任务历史。

---

## 4. 目录内子知识库（递归结构）

- 每个子目录（如 `core/`、`working-notes/`）下均有自己的 index.md，内容包括：
  - 本层级简介
  - 子文档/子目录导航表
  - 适用任务/关键词
  - AI协作指引（可继承或细化顶层规则）

---

## 5. 维护与更新说明

- 新增文档/目录时，请同步更新本 index.md 的导航表。
- 重要变更请记录在 `任务历史.md` 或相关笔记中。
- 鼓励定期梳理和归档历史任务，保持知识库简洁有序。

---

## 6. FAQ（可选）

- **Q: AI助手如何判断需要查阅哪些文档？**  
  A: 结合任务类型、关键词与本导航表，优先查阅最相关的文档，必要时递归进入子目录的 index.md。

- **Q: 如果找不到需要的信息怎么办？**  
  A: 先查阅本 index.md 和 `项目介绍 v0.3.md`，如仍有疑问，再考虑向用户提问。

---

# 结语

本 index.md 是整个知识库的入口和导航。请所有AI助手和新成员严格遵循本文件的指引，确保高效、低冗余的信息获取和协作。
