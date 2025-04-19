# iOS App 主流项目代码分析提示词

## 适用范围
适用于基于 Swift/SwiftUI/Objective-C 的主流 iOS 应用项目。

---

## 一、目录结构扫描与输出
- 递归扫描整个 iOS 项目目录（.xcodeproj、Sources、Resources、Tests、Pods 等），生成结构树（project-structure.md）。
- 注释主要目录和关键文件用途。

## 二、架构分析
- 识别并说明架构模式（MVC/MVVM/VIPER/Clean Architecture 等）。
- 分析视图层、控制器/视图模型、服务/网络层、数据持久化（CoreData/Realm/UserDefaults 等）。
- 依赖管理（CocoaPods/SPM）、技术栈说明。

## 三、新需求实现与协作
- 数据模型、页面、服务、资源文件新增/变更流程。
- 团队协作冲突规避与命名、分层、依赖注入、mock/测试降级等约定。

## 四、测试与发布
- 测试推进与用例规范（XCTest、Quick/Nimble、SnapshotTesting 等）。
- 发布流程（Xcode Build、TestFlight、App Store、证书/配置管理等）。

## 五、协作常见问题与建议
- 资源/依赖/证书管理、测试遗漏、多人协作冲突等处理建议。

---

### 一键提示词示例
```
请扫描本 iOS 项目，输出目录结构、架构分析、新需求实现与协作规范、测试与发布流程、常见协作问题与建议。
```
