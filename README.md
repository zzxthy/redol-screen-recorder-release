# Redol Screen Recorder 发布与反馈

这是 Redol Screen Recorder 的公开发布与问题反馈仓库。

产品源代码维护在私有仓库中。这个公开仓库主要用于：

- 发布可下载的安装包和版本说明
- 收集 Bug 反馈
- 收集功能建议
- 承接面向用户的支持讨论

English version: [readme-en.md](./readme-en.md)

## 下载

当前阶段优先提供 macOS 客户端：

- 当前最新版本：`v1.5.2`
- 发布日期：2026-06-21

- Apple Silicon Mac: [Redol-Screen-Recorder-Mac-arm64.dmg](https://github.com/zzxthy/redol-screen-recorder-release/releases/latest/download/Redol-Screen-Recorder-Mac-arm64.dmg)
- Intel Mac: [Redol-Screen-Recorder-Mac-x64.dmg](https://github.com/zzxthy/redol-screen-recorder-release/releases/latest/download/Redol-Screen-Recorder-Mac-x64.dmg)

Windows 客户端还在规划中，暂未发布。

## v1.5.2 更新

- 新增 Redol 账号中心，可查看登录邮箱、方案、权限状态、设备、最近验证时间和本地有效期。
- 支持刷新状态、管理订阅、切换账号和退出登录。
- 修复悬浮录屏工具条中账号弹窗按钮无法点击的问题。
- 修复较大弹窗被悬浮 HUD 裁切的问题。
- 修复原生高速导出中的平滑缩放效果，使导出结果和编辑预览保持一致。
- 保留后端统一权限控制能力，测试期免费使用策略可在服务端回收或调整。

## 反馈 Bug

如果你遇到问题，请新建一个 issue，并尽量提供以下信息：

- Redol Screen Recorder 版本号
- macOS 版本
- 你当时正在执行的操作
- 实际发生了什么
- 期望应该发生什么
- 截图、录屏、导出的诊断文件或日志

越具体的复现信息，越容易定位和修复问题。

## 功能建议

如果你希望改进某个录屏、编辑或导出流程，请使用 feature request 模板提交建议。

建议里最好包含：

- 你当前的使用场景
- 现有流程哪里不顺
- 你希望产品如何表现
- 类似产品或截图参考

## 常用链接

- Issues: https://github.com/zzxthy/redol-screen-recorder-release/issues
- Releases: https://github.com/zzxthy/redol-screen-recorder-release/releases
