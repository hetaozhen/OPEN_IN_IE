# OPEN_IN_IE

## 🚀 简介 / Introduction
在 Windows 10/11 逐渐移除 Internet Explorer 的今天，许多行业网站（如：政府内网、医疗挂号系统、教育考试网、财务网银）依然强行要求 IE 环境。

本项目是一个基于 HTA (HTML Application) 开发的轻量级桌面工具。它绕过了现代浏览器（Chrome/Edge）的默认关联，直接调用系统底层的 IE 内核引擎。

## ✨ 功能特性 / Features
纯净内核：强制调用系统 iexplore.exe 核心，不触发 Edge 重定向。

一键直达：内置常用行业网站快捷按钮，点击即开。

灵活扩展：支持手动输入 URL，并具备自动补全协议功能。

即用即走：点击按钮或跳转后，导航面板自动关闭，不占用系统资源。

零依赖：无需安装 Python/Node.js 或任何第三方运行库，双击即可运行。

## 🛠️ 技术栈 / Tech Stack
Language: VBScript / HTML / CSS

Engine: MSHTA (Microsoft HTML Application Host)

Encoding: ANSI (GB2312)

## 📦 安装使用 / Usage
下载仓库中的 IE打开助手.hta 文件。

(可选) 为其创建快捷方式并更换图标，以获得更好的桌面体验。

双击运行，选择对应系统或输入网址。

