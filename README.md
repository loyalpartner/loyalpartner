# 你好，我是 lee 👋

在 Linux 桌面栈上写代码 — 从 eBPF（Aya）到 Wayland 合成器，再到 GPU 渲染的桌面 shell。

整个职业生涯都在 Linux 桌面平台层：做过 Chromium OS 和 ChromeOS 衍生发行，参与过一款浏览器的发布，现在做企业级 Linux 安全桌面——namespace 隔离、网络虚拟化、剪贴板 / 打印机 / D-Bus 隔离、防截屏、窗口水印、BPF 驱动的进程与网络监控。

写代码主要为了验证想法，下面这些是反复回去打磨的：

- [**emskin**](https://github.com/loyalpartner/emskin) — 把 Emacs 当窗口宿主的嵌套 Wayland 合成器（Smithay），任意 Wayland/X11 程序作为 buffer 嵌入 Emacs。GNOME / KDE / Sway / COSMIC 全支持
- [**rway**](https://github.com/loyalpartner/rway) — Rust + Smithay 写的 Sway 兼容 Wayland 合成器。四层 crate 架构、~342 测试，复用 sway 配置 / `swaymsg` / waybar
- [**yac.vim**](https://github.com/loyalpartner/yac.vim) — 给 Vim 写的现代 IDE 后端，Zig daemon + LSP + tree-sitter + DAP + Copilot，内置 18 种语言。仅 Vim，不支持 Neovim（刻意选择）
- [**zskins**](https://github.com/loyalpartner/zskins) — 用 GPUI（Zed 的 GPU UI 框架）写的 Wayland 桌面三件套：状态栏 + launcher + 剪贴板后台
- [**puck**](https://github.com/loyalpartner/puck) — Frida 风格的 Linux 进程注入器（Rust）。已用于生产的 X11 防截屏实现，x86_64 + aarch64
- [**dbus-router**](https://github.com/loyalpartner/dbus-router) — 沙盒应用用的 dual-upstream D-Bus router，按规则把消息路由到 host bus 或 sandbox bus
- [**selfsync**](https://github.com/loyalpartner/selfsync) — 自托管 Chrome Sync 服务器（Rust + SQLite），实现 Chrome 原生同步协议，`--sync-url` 指过去即可。书签 / 密码 / 偏好不出本地
- [**fcitx5-anytalk**](https://github.com/loyalpartner/fcitx5-anytalk) — fcitx5 语音输入插件（C++ + Zig），接火山引擎 ASR

日常主力 **Rust**（系统层全栈）和 **Zig**（要性能、无 GC 的 daemon），也写过生产代码的还有 Go / C / C++ / Python / Ruby / Vim Script / Shell / Emacs Lisp。按问题选语言。

📍 成都，工作地点不限 · 📧 charlselee59@gmail.com
现合约即将到期，在看 Linux 桌面平台 / 安全 / 沙盒 / 系统级 Rust 方向的机会，欢迎聊。

## Star History

[![Star History Chart](https://api.star-history.com/chart?repos=emskin/emskin%2Cloyalpartner/selfsync&type=timeline&legend=top-left)](https://www.star-history.com/?repos=emskin%2Femskin%2Cloyalpartner%2Fselfsync&type=timeline&legend=top-left)
