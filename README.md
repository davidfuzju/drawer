# Drawer

**make it drawerable.**

把任意 macOS app 变成从屏幕边缘滑入/滑出的抽屉 —— 一个快捷键,秒呼秒收。聊天、AI 助手、终端、备忘:高频但不必常驻的 app,用完即走,不打断手头的事。

## 为什么做它

市面上的"边缘抽屉"工具几乎都是内置浏览器装网页(Slidepad 等),没有面向**原生 app** 的。Drawer 用 macOS Accessibility 直接驱动目标 app 的真实窗口,任何原生 app 都能被抽屉化 —— 尤其适合 Claude / ChatGPT 这类高频 AI 工具。

## 功能

- **边缘抽屉**:左 / 右 / 上 / 下任选,快捷键滑入滑出
- **多抽屉**:每个 app 绑各自快捷键;同一条边互斥、不同边独立
- **失焦自动收起**、**开机自启**
- **内置自动更新**(Sparkle),支持 Beta 频道

## 下载

见 [Releases](https://github.com/davidfuzju/drawer/releases)。要求 **macOS 26.5+(Apple Silicon)**。

> 当前版本未公证,首次打开可能被 Gatekeeper 拦下:右键 App → 打开,或到 系统设置 → 隐私与安全性 放行。

## 用法

1. 菜单栏 Drawer 图标 → **设置**
2. **＋** 选一个 app → 选边缘 → 录快捷键
3. 按快捷键呼入 / 呼出。再按收起,失焦也自动收起。

首次运行需在 **系统设置 → 隐私与安全性 → 辅助功能** 勾选 Drawer(控制窗口必需)。

## 自动更新

App 内「检查更新…」,或后台自动检查。想尝鲜:设置里打开「接收 Beta 更新」。

---

> 本仓库仅托管**发行产物**与**更新源**(`appcast.xml`);源码私有。
>
> Drawer · *make it drawerable.*
