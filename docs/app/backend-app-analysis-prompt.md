# 主流 App 服务端（后端）项目代码分析提示词

## 适用范围
适用于 Node.js、Java Spring Boot、Python Django/Flask、Go、.NET、Ruby on Rails 等主流 App 服务端项目。

---

## 一、目录结构扫描与输出
- 递归扫描后端项目目录（src、app、controllers、services、routes、models、config、migrations、tests 等），生成结构树（project-structure.md）。
- 注释主要目录和关键文件用途。

## 二、架构分析
- 识别并说明架构模式（MVC、DDD、RESTful、微服务等）。
- 分析路由、控制器、服务、数据访问层、认证/权限、配置、依赖注入、缓存等。
- 主要技术栈与依赖说明。

## 三、新需求实现与协作
- 数据模型、API、service、controller、middleware 新增/变更流程。
- 团队协作冲突规避、mock/测试降级、命名与分层等约定。

## 四、测试与发布
- 测试推进与用例规范（Jest、Mocha、Supertest、Pytest、JUnit、集成测试等）。
- 发布流程（本地/CI/CD 构建、环境变量、数据库迁移、API 文档同步、部署等）。

## 五、协作常见问题与建议
- 数据库迁移、接口变更、测试遗漏、多人协作冲突等处理建议。

---

### 一键提示词示例
```
请扫描本服务端项目，输出目录结构、架构分析、新需求实现与协作规范、测试与发布流程、常见协作问题与建议。
```
