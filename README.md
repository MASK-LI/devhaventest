# DevHaven - 项目管理工具

[![构建状态](https://github.com/用户名/devhaven/actions/workflows/build.yml/badge.svg)](https://github.com/用户名/devhaven/actions/workflows/build.yml)

一款专为开发者设计的桌面应用，帮助您组织和管理散落在各处的项目文件夹，实现一键用首选IDE打开项目的便捷体验。

## 项目痛点与解决方案

### 痛点
- 开发者往往在本地有多个公司、多个项目的代码仓库，分散在不同文件夹
- 寻找特定项目需要记忆或搜索路径，费时费力
- 不同项目可能需要使用不同的IDE打开
- 项目相关信息（如分支、文档等）缺乏集中管理

### 解决方案
DevHaven提供了一个集中式平台，将所有项目整合在一个界面中，方便查找和访问，并支持一键用对应IDE打开项目，大大提高了开发效率。

## 核心功能

- **项目组织**：按公司/文件夹层级组织项目
- **快速访问**：一键使用首选IDE（VS Code、IntelliJ IDEA、WebStorm等）打开项目
- **项目详情**：查看项目路径、Git分支、最后打开时间等信息
- **标签分类**：为项目添加标签和分类
- **数据库位置自定义**：便于备份和同步
- **深色/浅色主题**：支持切换界面主题
- **搜索功能**：快速查找项目

## 技术栈

- **前端**：Vue.js 3（组合式API）、Element Plus
- **样式**：UnoCSS
- **状态管理**：Pinia
- **数据库**：SQLite with better-sqlite3
- **桌面集成**：Electron

## 开发指南

### 环境要求

- Node.js 14+
- pnpm（推荐）或npm

### 安装与启动

1. 克隆仓库
2. 安装依赖：

```bash
pnpm install
```

3. 启动开发服务器：

```bash
pnpm dev
```

### 构建应用

构建当前平台版本：

```bash
pnpm build
```

构建特定平台版本：

```bash
# Windows
pnpm build:win

# macOS
pnpm build:mac

# Linux
pnpm build:linux
```

# 预览
![img](doc/image.png)
![img](doc/setting.png)
