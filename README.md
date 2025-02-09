# 语音邮件助手 (Voice Email Assistant)

一个基于语音识别的Outlook邮件助手，让您可以通过语音来快速创建邮件。

## 功能特点

- 通过快捷键（Ctrl+Alt+M）快速启动录音
- 实时语音识别
- 自动创建Outlook邮件草稿
- 简洁的悬浮窗口界面
- 支持拖拽移动窗口位置

## 安装说明

1. 确保您的系统满足以下要求：
   - Windows 10 或更高版本
   - Microsoft Outlook 已安装
   - Python 3.8 或更高版本（如果从源码安装）

2. 安装方式：

   ### 方式一：直接使用打包版本（推荐）
   
   1. 下载最新的发布版本
   2. 解压到任意目录
   3. 运行 `VoiceEmailAssistant.exe`

   ### 方式二：从源码安装

   1. 克隆仓库：
      ```bash
      git clone [repository-url]
      cd Win-Outlook-Agent
      ```

   2. 安装依赖：
      ```bash
      pip install -r requirements.txt
      ```

   3. 运行打包脚本：
      ```bash
      python build.py
      ```

   4. 在 `dist` 目录中找到打包好的应用程序

## 使用说明

1. 首次运行时，需要配置必要的环境变量（在 `.env` 文件中）
2. 启动应用程序后，它会在后台运行
3. 使用快捷键 `Ctrl+Alt+M` 打开录音窗口
4. 点击红色按钮开始录音
5. 再次点击按钮或按 `Esc` 停止录音
6. 使用 `Ctrl+Alt+Q` 退出应用程序

## 快捷键

- `Ctrl+Alt+M`: 打开/关闭录音窗口
- `Ctrl+Alt+Q`: 退出应用程序

## 注意事项

- 首次运行时请确保已正确配置 `.env` 文件
- 需要保持 Outlook 处于运行状态
- 确保系统麦克风权限已开启

## 问题反馈

如遇到问题，请检查：
1. 麦克风权限是否开启
2. Outlook 是否正常运行
3. 环境变量是否正确配置

## 许可证

[添加许可证信息]
