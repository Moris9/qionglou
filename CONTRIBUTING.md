# 贡献指南

首先，感谢您对 QiongLou 的支持，目前该组件库任在飞速的构建中，我们欢迎任何形式的贡献。

当然 如果您觉得文档中有任何不妥的地方，欢迎您提交 issue 或者 pr。

那么，如果您想要为 QiongLou 贡献代码，您可以按照以下步骤进行：

1. fork 本仓库
2. clone 到本地
3. 安装依赖
 ```bash
pnpm i
```
该命令会帮助您安装所有的依赖，如果您没有安装 pnpm，可以通过以下命令安装：
```bash
npm i -g pnpm
```
4. 启动文档预览
```bash
pnpm run start:docs
```
该命令会帮助您启动文档预览所有组件。
5. 在本地进行开发
```bash
pnpm run start
```
该命令会帮助您启动本地开发环境， 您可以将组件 添加到 `packages/qionglou` 目录下，然后在 `packages/qionglou/components.ts` 中导出。
在 `start/App.vue` 中导入您开发的组件进行测试预览。

### 结构
我们在每个目录下都添加了一个 `README.md` 文件，里面的内容或许对您有所帮助。
 - `packages/qionglou` 组件源码
 - `packages/themes` 组件样式
 - `docs` 文档源码
 - `start` 文档预览源码

### 提交规范

---
| type | 描述 |
| --- | --- |
| feat | 新增功能 |
| fix | 修复 bug |
| docs | 文档变更 |
| style | 代码格式（不影响功能，例如空格、分号等格式修正） |
| refactor | 代码重构 |
| perf | 改善性能 |
| test | 测试 |
| build | 变更项目构建或外部依赖（例如 scopes: webpack、gulp、npm 等） |
| ci | 更改持续集成软件的配置文件和 package 中的 scripts 命令，例如 scopes: Travis、Circle 等 |
| chore | 变更构建流程或辅助工具 |
| revert | 代码回退 |
---

### 提交代码
在您提交前，我们希望您认真阅读您的代码，确保没有任何错误并且使用项目中内置的 `vitest` 测试您的组件。

当您完成开发后，您可以提交代码到您 fork 的仓库，然后提交 pr 到本仓库，我们会尽快进行审核。

**我们希望在您提交代码前检查自己的仓库是否是最新的**

### 写在最后
我们不希望您抄袭现在市面上的任何一种组件库源码，我们希望您能够独立思考，独立开发，这对您的成长是有帮助的。
如果您遇到无法解决的问题，您可以通过联系项目管理者会协助您解决。

感谢以下开源项目的作者们，感谢您的阅读。

<a href="https://github.com/Jiangxue-team/qionglou/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Jiangxue-team/qionglou" />
</a>
