<h1 align="center">ClipDeck</h1>

<p align="center">
  <b>面向开发者的跨平台剪贴板管理器 · 极致轻量 · 本地优先 · 不碰服务器</b><br>
  <sub>A lightweight, local-first clipboard manager for developers. Windows & macOS.</sub>
</p>

<p align="center">
  <b>Windows 安装包仅 3 MB</b> —— 不是动辄上百 MB 的 Electron 应用。
</p>

<p align="center">
  <img src="docs/hero.png" width="380" alt="ClipDeck 主界面">
</p>

---

## 下载 Download

> 当前为公开测试版（免费）。点下方进入最新版本页，下载对应安装包：
>
> ### 👉 [前往最新版本下载页 / Latest Release](https://github.com/jiangnan0/clipdeck-app/releases/latest)

| 系统 | 文件 |
|---|---|
| **Windows** | `ClipDeck_x.x.x_x64-setup.exe`（推荐）或 `.msi` |
| **macOS (Apple Silicon)** | `ClipDeck_x.x.x_aarch64.dmg` |

## ⚠️ 安装时提示"来源不明 / 无法验证"？这不是病毒，正常现象

测试版**还没买代码签名证书**，所以系统会拦一下。按下面点两下就能装：

- **Windows**：弹出蓝色"Windows 已保护你的电脑" → 点左下角 **"更多信息" → "仍要运行"**。
- **macOS**：提示"无法打开，因为 Apple 无法检查" → 在访达里**右键点 App →"打开"**，或到 **系统设置 → 隐私与安全性** 点 **"仍要打开"**。

> 正式版会做签名/公证，届时不再有此提示。

## 它能做什么 Features

- **剪贴历史**：文本 / 图片 / 富文本，自动去重、最近用过的置顶、收藏常用片段
- **找得快**：模糊搜索 + 正则搜索；按类型筛选；按时间 / 类型 / 内容排序（可正/倒序）
- **全局快捷键唤起**：Windows `Ctrl+Shift+V` / macOS `⌘⇧V`，点一下直接粘回原应用
- **开发者多格式查看**：JSON / XML / YAML 折叠树，Base64 / JWT / 时间戳 / URL 一键解码，SQL / Shell 语法高亮，一键格式化 / 压缩成一行（连中文弯引号的 JSON 也认）
- **两条对比**：选两条做行级 diff，红绿高亮差异，确认后再粘
- **图片工具**：缩放查看、框选裁剪、本地 OCR 取字（都不上传）
- **隐私优先**：密码管理器内容自动跳过、敏感 token 不入库；历史只存在你本机
- **多语言 / 多主题**，无边框轻浮层界面
- **跨设备同步**（完整版）：通过你自己的网盘文件夹端到端加密同步，全程不经任何服务器

<p align="center">
  <img src="docs/preview-tree.png" width="330" alt="JSON/XML/YAML 折叠树查看">
  &nbsp;&nbsp;
  <img src="docs/compare.png" width="330" alt="两条对比 diff">
</p>
<p align="center"><sub>左：JSON / XML / YAML 折叠树查看　·　右：选两条做行级对比，红绿高亮差异</sub></p>

## 隐私 Privacy

ClipDeck **本地优先、不连任何服务器**：你的剪贴历史只保存在本机；图片 OCR、JSON/JWT 处理全部本地完成；跨设备同步走你自己的网盘、内容端到端加密，作者也看不到。

## 反馈 & 联系 Feedback & Contact

- **用着有问题 / 想提建议**：点上方 **[Issues](https://github.com/jiangnan0/clipdeck-app/issues)** 标签，新建一个 issue 描述一下（带截图更好）。
- **想要完整版（跨设备同步等）或商务合作**：同样在 Issues 留言，我会跟你联系。

非常感谢你帮忙测试 🙏

---

<sub>ClipDeck 为专有软件，本仓库仅用于分发安装包。© ClipDeck.</sub>
