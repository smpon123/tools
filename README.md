# ws-proxy-server

一个超轻量、跨平台的 WebSocket 正向/反向代理工具，用 Go 编写，单文件无依赖，完美支持 Windows / Linux / macOS / Android（Termux）。

[![Go](https://img.shields.io/badge/Go-1.23%2B-blue?logo=go)](https://go.dev)
[![License](https://img.shields.io/github/license/你的用户名/tools)](LICENSE)
[![Releases](https://img.shields.io/github/downloads/你的用户名/tools/total)](https://github.com/你的用户名/tools/releases)

## 特性

- 单文件，几 MB（upx 压缩后 < 3MB）
- 支持正向代理与反向代理
- 内置简洁 Web 管理界面
- 完全跨平台（已在 Windows、Linux、macOS、Android Termux 实测通过）
- 零外部依赖，go build 即用

## 快速开始（3 秒编译运行）

### 方法一：直接下载已编译好的版本（最快）
→ https://github.com/你的用户名/tools/releases

### 方法二：自己编译（推荐）

```bash
# 1. 克隆仓库
git clone https://github.com/你的用户名/tools.git
cd tools/ws-proxy-server

# 2. 下载依赖
go mod tidy

# 3. 一键编译所有平台
# Windows 用：
.\build.bat

# Linux / macOS / Termux 用：
chmod +x build.sh
./build.sh
