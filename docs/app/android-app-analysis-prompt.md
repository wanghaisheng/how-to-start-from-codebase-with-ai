# Android App 主流项目代码分析提示词

## 适用范围
适用于基于 Kotlin/Java 的主流 Android 应用项目。

---

## 一、目录结构扫描与输出
- 递归扫描 Android 项目目录（app/src、res、build.gradle、libs 等），生成结构树（project-structure.md）。
- 注释主要目录和关键文件用途。

## 二、架构分析
- 识别并说明架构模式（MVVM/MVP/MVC/Clean Architecture 等）。
- 分析 UI 层（Activity/Fragment/View）、ViewModel、Repository、Service、数据库（Room/Realm/SQLite）。
- 路由与导航、依赖管理（Gradle）、主要技术栈。

## 三、新需求实现与协作
- 数据模型、页面、ViewModel、Repository、Service、资源文件新增/变更流程。
- 团队协作冲突规避与命名、分层、依赖注入（Hilt/Dagger）、mock/测试降级等约定。

## 四、测试与发布
- 测试推进与用例规范（JUnit、Espresso、Mockito、Robolectric 等）。
- 发布流程（Gradle Build、Google Play、签名/证书管理等）。

## 五、协作常见问题与建议
- 资源/依赖/签名管理、测试遗漏、多人协作冲突等处理建议。

---

### 一键提示词示例
```
请扫描本 Android 项目，输出目录结构、架构分析、新需求实现与协作规范、测试与发布流程、常见协作问题与建议。
```
