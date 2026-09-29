# Marklith

**English** | [简体中文](README.zh-CN.md)

A desktop writing and workspace app for local Markdown documents.

[Downloads & release notes](https://github.com/Arrogantia/Marklith-releases/releases) · [Report an issue](https://github.com/Arrogantia/Marklith-releases/issues)

This repository hosts Marklith installers, release notes, and user documentation. It does not contain the application's source code.

## Download

Visit [Releases](https://github.com/Arrogantia/Marklith-releases/releases), choose a version, and download the installer under **Assets**. Check the release notes for supported systems, architectures, features, and known limitations.

[Download the Windows x64 installer (v0.1.0)](https://github.com/Arrogantia/Marklith-releases/releases/download/v0.1.0/Marklith_0.1.0_x64-setup.exe). The release includes **SHA256SUMS.txt** to verify your download.

The v0.1.0 installer is not digitally signed. Windows may display an unknown-publisher or SmartScreen prompt.

GitHub's automatic **Source code (zip)** and **Source code (tar.gz)** downloads are snapshots of this documentation repository. They are not installers and do not contain the Marklith application source code.

## Features

- **Markdown writing**: switch between source and live preview, with headings, lists, tables, code, math, and Mermaid diagrams.
- **Local workspaces**: open files or folders and organize documents with a file tree, outline, tabs, and search.
- **Documents and resources**: save and recover drafts, import images and attachments, inspect resource references, and export documents.
- **Personalization**: English and Chinese interfaces, multiple themes, custom keyboard shortcuts, and shortcut profiles.
- **Optional AI assistant**: multiple conversation tabs, history, Markdown replies, document context, and full-document translation through a compatible API or supported local CLI backend.

This is a project overview. Feature availability and verification status may differ between releases.

## Getting started

1. Download and run the Windows x64 installer. Keep an internet connection available: the installer downloads Microsoft Edge WebView2 Runtime if it is needed.
2. Launch Marklith. Use the **File** menu to open a Markdown file or a local folder, or create a new draft.
3. Write in the editor, switch between source and live preview as needed, and use **Save** or **Save As** to save your document.
4. Adjust the language, theme, and shortcuts in Settings. Enable an AI backend only if you want to use it.

Save your open documents before upgrading, and read the target version's upgrade notes. Preview releases are marked **Pre-release** on their release page.

## Common shortcuts

These are the Windows defaults. Existing custom profiles may differ; check **Settings → Shortcuts** for your active bindings.

| Action | Shortcut |
| --- | --- |
| New draft | Ctrl+N |
| Open file | Ctrl+O |
| Open folder | Ctrl+Shift+O |
| Save | Ctrl+S |
| Save As | Ctrl+Shift+S |
| Find in document | Ctrl+F |
| Toggle source and preview | Ctrl+/ |
| Open Settings | Ctrl+, |

## AI features and your data

AI backends are disabled by default. To use them, configure a compatible service or supported local CLI with your own account or API credentials. Available models, service charges, and backend compatibility depend on the provider and the release.

When you send a message, attach a document, or request a translation, the relevant content is passed to your selected backend. Agent file operations follow the app's permission settings. Features that require additional verification are indicated in the interface. Editing local documents does not require AI.

## Feedback

Please include the following when opening an [issue](https://github.com/Arrogantia/Marklith-releases/issues):

- Your Marklith version, operating system version, and device architecture.
- Steps to reproduce, the expected result, and what actually happened.
- Relevant screenshots or a minimal sample document.

Issues are public. Remove personal information, API keys, and sensitive document content from your examples and screenshots.

## About this repository

This repository maintains its own release history and publishes user documentation and binary release attachments. Application source code and development history are not provided here. Refer to the accompanying release materials for software and third-party licensing information.
