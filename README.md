<div align="center">
  <img src="./apps/app/icons/128x128.png" width="128" height="128" alt="Sulfur Fang Launcher Logo" />
  <h1>硫方怪启动器</h1>
  <p><strong>Sulfur Fang Launcher · 次世代 Minecraft 桌面客户端，全能、美观、全平台覆盖。</strong></p>

  <p>
    <a href="https://github.com/ljymm1131/mimicl/actions">
      <img src="https://img.shields.io/github/actions/workflow/status/ljymm1131/mimicl/build-windows.yml?style=for-the-badge&logo=github" alt="Windows Build" />
    </a>
    <a href="https://github.com/ljymm1131/mimicl/releases">
      <img src="https://img.shields.io/github/downloads/ljymm1131/mimicl/total?style=for-the-badge&logo=github" alt="Downloads" />
    </a>
    <a href="https://github.com/ljymm1131/mimicl/stargazers">
      <img src="https://img.shields.io/github/stars/ljymm1131/mimicl?style=for-the-badge&logo=github&color=ffb800" alt="Stars" />
    </a>
    <a href="COPYING.md">
      <img src="https://img.shields.io/badge/License-GPL_3.0-blue.svg?style=for-the-badge" alt="License" />
    </a>
  </p>

  <p>
    <a href="https://github.com/ljymm1131/mimicl">GitHub 仓库</a> ｜
    <a href="https://github.com/ljymm1131/mimicl/releases/latest">下载最新版</a> ｜
    <a href="CONTRIBUTING.md">参与贡献</a>
    ｜ <a href="CODE_OF_CONDUCT.md">行为准则</a>
  </p>
</div>

---

**Sulfur Fang Launcher** 是一款免费、开源、跨平台的 Minecraft Java 版第三方启动器，支持在一个客户端中搜索、安装和更新来自 Modrinth 与 CurseForge 的模组、整合包、资源包和光影，并提供实例管理、多种账户认证、个性化外观与实验室工具。

> **衍生作品声明**：Sulfur Fang Launcher 基于 [Axolotl Launcher](https://github.com/Axolotl-Launcher/Axolotl)（原版权 Garbage Human Studio，GPL-3.0-only）修改而来，沿用 GPL-3.0 许可证。原项目的版权与许可证声明完整保留，详见 [COPYING.md](COPYING.md)。

本项目基于 [Modrinth App](https://github.com/modrinth/code) 构建，移除了不适用于本项目的商业化模块，专注于提供纯净、无广告的桌面启动体验。

_(注：本项目是调用 Modrinth 公开 API 的独立客户端，与 Rinth, Inc. 无任何关联。)_

## 核心优势

- **真跨平台体验**：告别繁琐的环境配置，原生支持 Windows、macOS（完美兼容 Intel 与 Apple Silicon）及各类主流 Linux 发行版。
- **现代化内容生态**：集成 Modrinth 和 CurseForge，可在启动器中一键浏览。游戏实例、整合包、模组、资源包及光影均可一键安装与升级，彻底告别手动管理依赖的痛苦。
- **高度定制化**：无论是主题色调、背景图片，还是离线皮肤，核心功能与视觉展现均由你自由支配。
- **All in one 全新体验**：启动器内置 “实验室” 功能，囊括种子地图、投影工坊等海量实用工具。

## 下载与安装

请前往 [GitHub Releases](https://github.com/ljymm1131/mimicl/releases/latest) 下载适合你操作系统的最新安装包。

> **关于未签名构建**：当前发布的为社区构建版本，未使用代码签名证书。在 Windows 上安装时，系统可能弹出 SmartScreen“未知发布者”提示，点击“仍要运行”即可继续，功能完全正常。自动更新功能暂未启用，请手动下载新版本更新。

| 系统平台                | 推荐下载文件                              | 说明 |
| ----------------------- | ----------------------------------------- | ---- |
| **Windows** (10/11 x64) | 下载 `.exe` (NSIS) 安装程序               | 由 `build-windows.yml` 自动构建 |
| **macOS**               | 通用 `.dmg` 镜像文件                      | 需基于源码自行构建 |
| **Linux** (x64)         | `.AppImage`、`.deb`、`.rpm` 多种格式      | 需基于源码自行构建 |

> 当前仅提供 Windows 的自动构建（见 [`.github/workflows/build-windows.yml`](.github/workflows/build-windows.yml)）。macOS 与 Linux 用户可参照 [CONTRIBUTING.md](CONTRIBUTING.md) 从源码编译。

## 参与项目开发

Sulfur Fang Launcher 的进步离不开社区的反馈与贡献。
如果遇到 Bug 或有新的功能点子，欢迎提交 Issue。如需搭建本地开发环境或查阅打包发布规范，请阅读详细的 [贡献指南 (CONTRIBUTING.md)](CONTRIBUTING.md)。
参与社区和贡献代码前，也请先阅读[行为准则 (CODE_OF_CONDUCT.md)](CODE_OF_CONDUCT.md)。

---

<sub>Sulfur Fang Launcher 是 Axolotl Launcher 的衍生修改版本，以 GPL-3.0-only 许可证发布。</sub>
