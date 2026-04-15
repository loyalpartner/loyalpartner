# 你好，我是 lee 👋

**Linux 桌面平台工程师。** 整个栈我都做 — 从内核侧（用 Aya 写 eBPF）一路到 Wayland 合成器和 GPU 渲染的桌面 shell。Rust 全栈，Zig 用在合适的地方。

📍 成都 · 📧 charlselee59@gmail.com · 👀 想换工作

---

## 我做过的事

整个职业生涯都在 Linux 桌面平台层，分三段：

- 在一家操作系统公司做 **Chromium OS** —— 系统底层 + ChromeOS 衍生发行 + 浏览器发布
- **期间主导/参与发布过一款浏览器**
- 现在做 **企业级 Linux 安全桌面** —— namespace 隔离、网络虚拟化、剪切板 / 打印机 / D-Bus 隔离、防截屏、窗口水印、BPF 驱动的进程与网络监控

三段工作的共同点：每一段都在让 Linux 桌面**更可控、更可隔离**。

---

## 旗舰项目（兴趣驱动 · 全部开源）

我写代码是为了验证想法，下面这些是我反复回去打磨的：

| 项目 | 一句话 |
|---|---|
| [**emskin**](https://github.com/loyalpartner/emskin) | 一个把 Emacs 当窗口宿主的 Wayland 合成器，让任意 Wayland/X11 程序作为 buffer 嵌入 Emacs。GNOME / KDE / Sway / COSMIC 全支持 |
| [**rway**](https://github.com/loyalpartner/rway) | Rust + Smithay 写的 **Sway 兼容 Wayland 合成器**。四层 crate 架构、~342 测试、复用 sway 配置 / `swaymsg` / waybar |
| [**yac.vim**](https://github.com/loyalpartner/yac.vim) | 给 Vim 写的现代 IDE 后端 —— Zig daemon + LSP + tree-sitter + DAP + Copilot，自带 18 种语言。**仅 Vim，不支持 Neovim**（明确选择） |
| [**zskins**](https://github.com/loyalpartner/zskins) | 用 GPUI（Zed 的 GPU UI 框架）写的 Wayland 桌面三件套：状态栏 + launcher + 剪贴板后台 |
| [**puck**](https://github.com/loyalpartner/puck) | Frida 风格的 Linux 进程注入器（Rust）。**生产场景：用它实现 X11 防截屏**。x86_64 + aarch64 |
| [**dbus-router**](https://github.com/loyalpartner/dbus-router) | 给沙盒应用用的 dual-upstream D-Bus router —— 按规则把消息路由到 host bus 或 sandbox bus |
| [**fcitx5-anytalk**](https://github.com/loyalpartner/fcitx5-anytalk) | fcitx5 语音输入插件（C++ + Zig），接火山引擎 ASR |

---

## 我能干什么

**Linux 桌面整层栈，从 BPF 到 GPU 渲染都自己做过，没有断点。**

- **写过 2 个 Wayland 合成器** —— `rway`（Sway 兼容，Rust + Smithay，4 层 crate 架构、~342 测试、复用 sway 配置 / `swaymsg` / waybar）和 `emskin`（嵌 Emacs 的 Wayland 合成器，**44⭐**，跨 GNOME / KDE / Sway / COSMIC）。X11 (Xorg) 和 Wayland (Smithay / wlroots / KWin) **两侧源码都通读过**
- **企业安全桌面整套隔离能力都自己写过** —— namespace 隔离、网络虚拟化、剪切板 / 打印机 / D-Bus 隔离、防截屏（用自写的 `puck` 注入器实现）、窗口水印；docker / firejail / bwrap 都研究过
- **eBPF 落到生产** —— Aya 写过进程监控和网络流量监控、Cilium 用过、BPF 驱动的沙箱设计落到产品里。**同一种语言（Rust）从用户态 daemon 一路打到内核态 BPF 程序**
- **给 Vim 写过一个 IDE 后端** —— `yac.vim`：Zig daemon 实现 LSP + tree-sitter + DAP + Copilot + fuzzy picker，自带 18 种语言。明确不支持 Neovim（设计选择）
- **Linux 桌面平台履历完整** —— 在一家操作系统公司做过 Chromium OS、期间推过一款浏览器，现在做企业级 Linux 安全桌面


---

## 我用过的语言

写过生产代码的：**Rust · Zig · Go · C · C++ · Python · Ruby · Vim Script · Shell · Emacs Lisp**（共 10 种）

当前默认 **Rust**（系统层全栈）+ **Zig**（要快、无 GC 的 daemon），但每个项目按问题选语言，不站队。

---

## 联系

在听 **Linux 桌面平台 / 安全 / 沙盒 / 系统级 Rust** 相关方向的机会。

📧 charlselee59@gmail.com
