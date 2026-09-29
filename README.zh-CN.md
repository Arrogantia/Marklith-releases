# Marklith

[English](README.md) | **简体中文**

面向本地 Markdown 文档的桌面写作与工作区管理工具。

[下载与版本说明](https://github.com/Arrogantia/Marklith-releases/releases) · [问题反馈](https://github.com/Arrogantia/Marklith-releases/issues)

本仓库用于发布 Marklith 安装包、版本说明和使用文档，不包含应用源代码。

## 下载

进入 [Releases 页面](https://github.com/Arrogantia/Marklith-releases/releases)，选择对应版本，在 **Assets** 中下载安装包。支持的系统、架构、功能和已知问题以该版本说明为准。

[下载 Windows x64 安装包（v0.1.0）](https://github.com/Arrogantia/Marklith-releases/releases/download/v0.1.0/Marklith_0.1.0_x64-setup.exe)。该版本附带 SHA256SUMS.txt，供核对下载文件。

v0.1.0 安装包尚未进行数字签名，Windows 可能显示未知发布者或 SmartScreen 提示。

GitHub 自动提供的 **Source code (zip)** 和 **Source code (tar.gz)** 只是本说明仓库的快照，不是安装包，也不包含 Marklith 应用源码。

## 功能概览

- **Markdown 写作**：源码与即时预览切换，支持标题、列表、表格、代码、数学公式与 Mermaid 图表。
- **本地工作区**：打开文件或文件夹，通过文件树、大纲、标签页和搜索组织文档。
- **文档与资源管理**：草稿保存与恢复、图片及附件导入、资源引用检查、文档导出。
- **个性化设置**：中文与英文界面、多种主题、自定义快捷键及快捷键方案。
- **可选 AI 助手**：多对话标签、历史记录、Markdown 回复、文档上下文和整篇翻译；可配置兼容 API 或受支持的本机 CLI 后端。

以上是项目功能概览，不代表所有发布版本均已包含或验证全部功能。

## 开始使用

1. 下载 Windows x64 安装包并运行。安装程序在需要时会下载安装 Microsoft Edge WebView2 Runtime，请保持网络连接。
2. 启动 Marklith，通过“文件”菜单打开 Markdown 文件或本地文件夹，也可以新建草稿。
3. 在编辑器中写作，按需切换源码与即时预览，通过“保存”或“另存为”保存文档。
4. 在设置中调整语言、主题和快捷键；按需开启 AI 后端。

升级前请保存正在编辑的文档，并阅读目标版本的升级说明。预发布版本会在版本页面标注 **Pre-release**。

## 常用快捷键

以下为 Windows 默认方案；已有自定义方案可能不同，请以“设置 → 快捷键”为准。

| 操作 | 快捷键 |
| --- | --- |
| 新建草稿 | Ctrl+N |
| 打开文件 | Ctrl+O |
| 打开文件夹 | Ctrl+Shift+O |
| 保存 | Ctrl+S |
| 另存为 | Ctrl+Shift+S |
| 文档内查找 | Ctrl+F |
| 切换源码与预览 | Ctrl+/ |
| 打开设置 | Ctrl+, |

## AI 功能与数据

AI 后端默认关闭。启用后需要自行配置兼容服务或受支持的本机 CLI，并使用自己的账户或 API 凭据。可用模型、服务费用及后端兼容范围由对应服务和版本说明决定。

发送消息、附加文档或进行翻译时，相关内容会交给所选后端处理。Agent 文件操作遵循应用中的权限设置；需要额外验证的能力会在界面中提示。普通本地文档编辑无需启用 AI。

## 问题反馈

请在 [Issues](https://github.com/Arrogantia/Marklith-releases/issues) 中提供：

- Marklith 版本、系统版本与设备架构。
- 可复现的操作步骤、预期结果和实际结果。
- 必要的截图或最小示例文档。

这是公开反馈区，请移除示例和截图中的个人信息、API 密钥及敏感文档内容。

## 关于此仓库

此仓库独立维护发布记录，仅公开使用说明和已发布的二进制附件。应用源码及开发提交历史不在此仓库中提供。安装包及其所含第三方组件的许可信息以对应版本随附说明为准。
