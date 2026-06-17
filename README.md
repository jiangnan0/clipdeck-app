<h1 align="center">ClipDeck</h1>

<p align="center">
  <b>面向开发者的跨平台剪贴板管理器 · 极致轻量 · 本地优先 · 不碰服务器</b><br>
  <b>A lightweight, local-first clipboard manager for developers · Windows &amp; macOS</b>
</p>

<p align="center">
  <b>Windows 安装包仅 3 MB / Windows installer is just ~3 MB</b> —— 不是动辄上百 MB 的 Electron 应用 / not a 100 MB+ Electron app.
</p>

<p align="center">
  <img src="docs/hero.png" width="380" alt="ClipDeck">
</p>

---

## 下载 · Download

> 公开测试版（免费）。点下方进入最新版本页，下载对应安装包。<br>
> Public beta (free). Open the latest release below and grab the installer for your OS.
>
> ### 👉 [前往最新版本 · Latest Release](https://github.com/jiangnan0/clipdeck-app/releases/latest)

| 系统 · OS | 文件 · File |
|---|---|
| **Windows** | `ClipDeck-Windows.exe`（推荐 · recommended）或 · or `.msi` |
| **macOS (Apple Silicon)** | `ClipDeck-macOS.dmg` |

## ⚠️ 安装时提示"来源不明 / 无法验证"？· Seeing an "unidentified developer" warning?

这不是病毒——测试版还没买代码签名证书，系统会拦一下。按下面点两下就能装。<br>
It's not malware — the beta isn't code-signed yet, so the OS warns. Two clicks and you're in:

- **Windows**：蓝色"Windows 已保护你的电脑" → 左下 **"更多信息" → "仍要运行"**。<br>
  Blue SmartScreen → **"More info" → "Run anyway"**.
- **macOS**：提示"无法打开" → 访达里**右键 App → "打开"**，或 **系统设置 → 隐私与安全性 → "仍要打开"**。<br>
  Right-click the app → **"Open"**, or **System Settings → Privacy &amp; Security → "Open Anyway"**.

> 正式版会做签名/公证，届时不再有此提示。· The stable release will be signed/notarized.

## 它能做什么 · Features

- **剪贴历史 · Clipboard history**：文本 / 图片 / 富文本，自动去重、最近用过的置顶、收藏常用片段。<br>
  Text / image / rich text — auto-dedup, most-recent on top, pin favorites.
- **找得快 · Fast find**：模糊搜索 + 正则搜索；按类型筛选；按时间 / 类型 / 内容排序（可正/倒序）。<br>
  Fuzzy + regex search, type filter, sort by time / type / content (asc or desc).
- **全局快捷键 · Global hotkey**：可自定义；点一下直接粘回原应用。<br>
  Customizable; one click pastes straight back into your app.
- **开发者多格式 · Developer formats**：JSON / XML / YAML 折叠树，Base64 / JWT / 时间戳 / URL 一键解码，SQL / Shell 高亮，格式化 / 压缩。<br>
  Folding trees, one-click decoders, syntax highlight, format / minify.
- **两条对比 · Diff two**：选两条做行级 diff，红绿高亮差异。<br>
  Pick two entries for a line-level diff.
- **图片工具 · Image tools**：缩放查看、框选裁剪、本地 OCR 取字（不上传）。<br>
  Zoom, crop, and local OCR — never uploaded.
- **隐私优先 · Privacy-first**：密码管理器内容自动跳过、敏感 token 不入库、历史只存本机。<br>
  Skips password-manager content, drops secret tokens, history stays on-device.
- **跨设备同步 · Cross-device sync（完整版 · Pro）**：通过你自己的网盘文件夹端到端加密同步，全程不经任何服务器。<br>
  End-to-end encrypted through your own cloud folder — no server involved.

<p align="center">
  <img src="docs/preview-tree.png" width="330" alt="folding tree">
  &nbsp;&nbsp;
  <img src="docs/compare.png" width="330" alt="diff two">
</p>
<p align="center"><sub>左 · Left：JSON / XML / YAML 折叠树查看 (folding tree)　·　右 · Right：选两条做行级对比 (line diff)</sub></p>

## 隐私 · Privacy

ClipDeck **本地优先、不连任何服务器**：剪贴历史只保存在本机；图片 OCR、JSON/JWT 处理全部本地完成；跨设备同步走你自己的网盘、内容端到端加密，作者也看不到。<br>
ClipDeck is **local-first and never talks to a server**: your clipboard history stays on your machine; OCR and JSON/JWT processing run fully locally; cross-device sync goes through your own cloud folder with end-to-end encryption — even the author can't see it.

## 反馈 & 联系 · Feedback &amp; Contact

- **用着有问题 / 想提建议** · Found a bug or have an idea：点上方 **[Issues](https://github.com/jiangnan0/clipdeck-app/issues)** 新建一个（带截图更好 · screenshots help）。
- **想要完整版（跨设备同步等）或商务合作** · Want the full version or a partnership：同样在 Issues 留言，我会跟你联系 · leave an issue and I'll reach out.

非常感谢你帮忙测试 🙏 · Thanks a lot for helping test!

---

<sub>ClipDeck 为专有软件，本仓库仅用于分发安装包。Proprietary software; this repository only distributes installers. © ClipDeck.</sub>
