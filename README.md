# 🌿 Gentra

> Windows 本地效率中枢 —— 剪贴板、备忘录、文件清理，一应俱全，数据全程本地不上传。

Gentra 是一款运行于 Windows 的桌面效率工具，把**计划提醒、专注计时、剪贴板历史、备忘录、磁盘清理和批量文件工具**整合到一个应用里。所有数据保存在本地，不收集、不上传任何信息。

![version](https://img.shields.io/badge/version-1.3.1-2f6f63) ![platform](https://img.shields.io/badge/platform-Windows%2010%2F11-2f6f63) ![license](https://img.shields.io/badge/license-免费个人使用-2f6f63)

<p align="center">
  <img src="README-assets/final/01-hero.png" alt="Gentra Windows 本地效率中枢" width="100%" />
</p>

## 🎬 12 秒了解 Gentra

<p align="center">
  <a href="README-assets/final/gentra-feature-tour.mp4">
    <img src="README-assets/final/gentra-feature-tour.gif" alt="Gentra 功能演示：工作台、计划、专注、剪贴板和安全清理" width="84%" />
  </a>
</p>

<p align="center"><sub>点击动图可打开 1920×1080 高清 MP4。</sub></p>

## 🖼️ 产品特点

<table>
  <tr>
    <td width="50%">
      <img src="README-assets/final/02-plan-focus.png" alt="Gentra 计划与专注" />
      <p align="center"><b>计划与专注</b><br/>严谨时间逻辑、优先级、Windows 通知与精准计时</p>
    </td>
    <td width="50%">
      <img src="README-assets/final/03-clipboard-memo.png" alt="Gentra 剪贴板与备忘录" />
      <p align="center"><b>剪贴板与备忘录</b><br/>自动记录、搜索收藏、快速复制，数据全部保存在本地</p>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <img src="README-assets/final/04-safe-storage.png" alt="Gentra 安全清理" />
      <p align="center"><b>安全清理</b><br/>选择扫描范围、逐项审查候选、系统目录强制保护、文件只进回收站</p>
    </td>
  </tr>
</table>

---

## ✨ 功能特性

> 按 **Ctrl + K** 可打开快捷面板，搜索功能、计划、备忘和剪贴板记录。

### 🏠 工作台
首页集中展示最近剪贴板、近期计划、备忘数量、磁盘状态和下载目录信息，各卡片可一键跳转。

### 📋 剪贴板
- 后台自动记录复制的 **文本 / 链接 / 代码 / 图片**，类型自动识别
- 一键复制回、收藏、搜索、6 类筛选
- 支持图片剪贴板（缩略图 + 原图查看 + 复制回）
- 暂停记录、退出清空、最大数量限制，均可配置

### 🗒️ 备忘录
- 快速记录标题与正文，支持编辑、搜索、置顶和排序
- 从剪贴板一键生成备忘，所有内容仅保存在本地

### 📅 计划
- 管理开始时间、截止时间、提醒、地点、备注和优先级
- 支持今天/即将开始/全部/已完成视图与优先级排序
- Windows 原生通知提醒并播放系统提示音

### ⏱️ 专注
- 专注计时器支持小时与分钟滚轮设置、暂停继续和跨重启恢复
- 自动保存专注历史，展示每日目标与最近 7 天趋势
- 专注结束后发送 Windows 通知与系统提示音

### 💾 存储与文件
| 子功能 | 说明 |
|---|---|
| 磁盘概览 | 真实磁盘用量 + 超 85% 告警 |
| 大文件扫描 | 选目录 + 大小区间 + 搜索 + 随时停止 |
| 下载目录 | 真实统计 + 一键清理 |
| 重复文件 | SHA-256 内容比对，精确识别 |
| 文件工具 | 批量重命名 + 按类型分类整理 |
| 安全清理 | 扫描安装包、压缩包、未完成下载、临时文件和崩溃转储，确认后移入回收站 |

### ⚙️ 设置
- 开机自启、最小化到系统托盘、关闭时最小化
- 深色 / 浅色 / 跟随系统主题
- 剪贴板记录策略联动（启用 / 最大数量 / 记录图片 / 退出清空）
- 每日专注目标、专注历史统计与 Ctrl + K 快捷面板开关
- 数据导出（JSON 备份）
- **自动更新**（启动自动检查 GitHub Release，也可手动检查；检查到更新展示更新内容，允许暂不更新；每小时自动检查，发现新版红点提示）

---

## 📥 下载安装

1. 前往 [Releases](https://github.com/zhixi0723/todolist-updates/releases) 下载最新版 `Gentra Setup x.x.x.exe`
2. 双击运行安装（安装向导会显示用户协议、可自选安装路径、完成后可选运行）
3. 首次安装时 Windows 可能提示"未知发布者"（未购买代码签名证书），点 **"仍运行"** 即可，不影响使用

> 支持自动更新：安装后会自动检查新版本，发现更新后由用户确认下载和安装。

---

## 🔒 隐私

- **全部数据本地存储**：`%APPDATA%\Gentra`
- 剪贴板、备忘录、设置等不离开你的电脑
- 不进行任何数据收集或上传
- 可随时在「设置 → 关于」导出数据备份

文件清理操作只移入**回收站**（可恢复），不永久删除。

---

## 🛠 技术栈

- **Electron** + **React** + **Vite** + **Tailwind CSS**
- **electron-updater** 自动更新
- 文件操作、剪贴板监听和磁盘扫描使用 Node / Electron 内置能力实现

---

## 📌 系统要求

- Windows 10 / 11（64 位）

---

## 💬 反馈

遇到 Bug 或有功能建议，欢迎在 [Issues](https://github.com/zhixi0723/todolist-updates/issues) 提交，或发邮件至 zhixi0723@163.com。

---

## 📄 许可

本软件供个人免费使用。如需商业使用，请联系作者。

---

> 应用由 Gentra 团队开发维护。









