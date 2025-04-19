# 主流全栈应用项目代码分析提示词

## 适用范围
适用于 Next.js+Node.js、React+Express、Vue+Spring Boot、Flutter+Firebase、MERN、MEVN、JAMStack 等主流全栈应用项目。

---

## 一、目录结构扫描与输出
- 递归扫描全栈项目目录（frontend、backend、api、server、src、database、mobile、docs 等），生成结构树（project-structure.md）。
- 注释主要目录和关键文件用途。

## 二、架构分析
- 识别并说明前后端分层、核心模块、API 通信、数据库/存储、状态管理、权限、第三方服务等。
- 分析技术栈与依赖（如 RESTful、GraphQL、WebSocket、ORM、CI/CD 等）。

## 三、新需求实现与协作
- schema/model、前端页面、后端 API、hooks/service、新端适配等新增/变更流程。
- 团队协作冲突规避、mock/测试降级、命名与分层等约定。

## 四、测试与发布
- 前后端、数据库、多端测试推进与用例规范（Jest/Vitest/RTL/Cypress/Supertest/Playwright 等）。
- 发布流程（本地/CI/CD 构建、环境变量、数据库迁移、API 文档同步、部署等）。

## 五、协作常见问题与建议
- 接口/数据流误用、环境配置、数据库迁移、测试遗漏、多人协作冲突等处理建议。

---

### 一键提示词示例
```
请扫描本全栈应用项目，输出目录结构、架构分析、新需求实现与协作规范、测试与发布流程、常见协作问题与建议。
```
