<div align="center">

# 🛰️ Rcst Network Studio

### 用 Material You 的温度，做有烟火气的社区产品

[![在线预览](https://img.shields.io/badge/%E5%9C%A8%E7%BA%BF%E9%A2%84%E8%A7%88-hmnl3.20110208.xyz-6750a4?style=flat-square)](https://hmnl3.20110208.xyz)
[![GitHub Org](https://img.shields.io/badge/%E7%BB%84%E7%BB%87-Rcst--Network--Studio-181717?style=flat-square&logo=github)](https://github.com/Rcst-Network-Studio)

</div>

---

👋 你好！**Rcst Network Studio** 是一个专注于**实时互动社区**与**直播生态**的独立开发工作室。我们偏爱 [Material Design 3](https://m3.material.io/) 的设计语言，追求「原生、轻量、可触控」的 Web 与跨端体验。

## ✨ 旗舰项目

<table>
  <tr>
    <td width="58%" valign="top">
      <h3>📡 HMNL 直播讨论站 <sup>VER.3</sup></h3>
      <p>一个集 <b>直播观看 · 话题发帖 · 实时聊天 · AI 助手</b> 于一体的社区平台。</p>
      <ul>
        <li>🎬 多频道直播（HLS）与直播管理后台</li>
        <li>💬 公共聊天室 + 帖子评论系统</li>
        <li>📰 放送广场 / 社区动态 / 消息通知</li>
        <li>🤖 内置 AI 对话助手</li>
        <li>👥 完整角色体系：超管 / 管理员 / 主播 / 入驻 / 用户</li>
      </ul>
      <p>
        <a href="https://hmnl3.20110208.xyz">🌐 在线体验</a> &nbsp;·&nbsp;
        <a href="https://github.com/Rcst-Network-Studio/hmnl3">📦 源代码</a>
      </p>
    </td>
    <td width="42%" valign="middle" align="center">
      <img src="https://img.shields.io/badge/状态-持续迭代-2e7d32?style=for-the-badge" alt="status"/><br><br>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="ts"/><br>
      <img src="https://img.shields.io/badge/mdui-Material_3-6750a4?style=for-the-badge&logo=materialdesign&logoColor=white" alt="mdui"/><br>
      <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="supabase"/>
    </td>
  </tr>
</table>

## 🧰 技术栈

| 领域 | 选型 |
| --- | --- |
| **前端运行时** | 原生 TypeScript SPA（无重型框架 · 自研 History 路由 + AbortSignal 页面生命周期） |
| **UI 组件** | [mdui 2](https://www.mdui.org) / Material Design 3 Web Components |
| **构建** | Vite 5 |
| **后端** | Supabase（PostgreSQL + Auth + Edge Functions + Storage） |
| **媒体** | hls.js 直播流播放 |
| **内容** | EasyMDE + marked + DOMPurify（Markdown 安全渲染） |
| **跨端** | 原生 Android（Kotlin + Jetpack Compose + M3）、WinUI 3 桌面端 |

## 🌐 仓库导航

| 仓库 | 说明 |
| --- | --- |
| [`hmnl3`](https://github.com/Rcst-Network-Studio/hmnl3) | HMNL 直播系统 VER.3 主仓库（Web 端 + Edge Functions） |
| [`.github`](https://github.com/Rcst-Network-Studio/.github) | 组织配置与主页 README |

## 💡 设计哲学

- 🧬 **原生优先** — 用 Web Components 与原生 TS，减少抽象层，追求首屏与交互的极致轻快。
- 🎨 **Material You** — 种子色主题、动态深浅色、跟随系统；触控尺寸与动效对齐 MD3 规范。
- 🔒 **安全为本** — DOMPurify 防 XSS、Supabase RLS 行级权限、密钥经环境变量注入、凭据不入库。
- 📱 **跨端一致** — Web / Android / 桌面共享同一后端与 MD3 视觉语言。

## 📫 联系我们

- 🌍 官网 / 在线预览：<https://hmnl3.20110208.xyz>
- 🐛 问题与建议：[Issues](https://github.com/Rcst-Network-Studio/hmnl3/issues)
- 🤝 协作：欢迎通过 Issue 或 Pull Request 参与

<div align="center">

---

<sub>© 2026 Rcst Network Studio · 用 ❤️ 与 TypeScript 构建</sub>

</div>
