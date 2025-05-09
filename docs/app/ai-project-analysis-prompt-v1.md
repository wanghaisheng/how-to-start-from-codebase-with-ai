# 新项目代码分析与协作规范文档自动生成 - 优化提示词 v1

## 目标
针对新项目，自动分析代码库、生成结构化协作文档，聚焦新需求快速实现与多人协作冲突规避。

---

## 一、目录结构扫描与输出
- 递归扫描整个项目文件夹，生成详细的目录结构树（建议输出到 `project-structure.md`）。
- 简要注释每个主要目录和关键文件的用途。

## 二、项目架构文档
- 生成清晰的架构总览（如 `architecture-overview.md`），包括分层设计、核心模块、数据流、主要技术栈说明。
- 重点说明前端、后端、移动端（如有）、数据库/存储、API、插件等各层职责与协作关系。

## 三、新需求实现与协作规范
- 生成新需求实现流程文档（如 `feature-development-guide.md`），涵盖 schema 新增、页面开发、hooks/service 新增与变更的标准步骤。
- 强调如何避免多人协作时的冲突（如 schema/service 变更同步、PR/Issue 说明、文档同步、主导人认领机制等）。
- 规范分层、命名、路径、mock/测试环境降级等团队约定。

## 四、测试流程与用例规范
- 输出测试推进与用例撰写规范文档（如 `testing-and-release-guide.md`），包括测试文件放置、命名、mock 策略、覆盖要求、CI 流程等。
- 明确每个核心模块必须有 smoke/unit/integration 测试，测试推进需自动检测缺失用例并输出清单。

## 五、发布流程与插件管理
- 说明标准的发布流程（如 `release-process.md`），包括测试、构建、真机验证、CI/CD、文档同步 checklist。
- 输出已集成的 Capacitor 插件清单及其用途，详细说明新增插件的标准流程（安装、注册、适配层封装、测试、文档同步等）。

## 六、可选：协作常见问题与处理建议
- 总结常见协作冲突、遗漏、测试覆盖不足等问题的处理建议，鼓励主动沟通与文档同步。

---

### 使用建议
- 以上每一部分都应有结构化的目录、分点说明、操作步骤和协作注意事项，语言简明、对新手友好。
- 所有输出文件均放在 `new-docs` 文件夹，便于团队成员随时查阅与维护。
- 如遇特殊业务场景或团队约定，可在文档末尾补充“常见问题与团队约定”专栏。

---

## 一键提示词示例

```
请自动扫描本项目代码库，输出到 new-docs 文件夹，内容包括：
1. 递归扫描并注释目录结构（project-structure.md）。
2. 生成架构总览（architecture-overview.md），分层、核心模块、数据流、技术栈。
3. 生成新需求实现与协作规范（feature-development-guide.md），涵盖 schema、页面、hooks、服务等新增流程与冲突规避。
4. 生成测试流程与用例书写规范（testing-and-release-guide.md）。
5. 生成发布流程与 Capacitor 插件管理说明（release-process.md）。
6. 可选：输出协作常见问题与处理建议。
```

---

如需进一步细化某一部分（如测试覆盖、插件适配、多人协作冲突规避等），可在提示词中补充具体关注点。
