# macOS 客户端配置教程（Clash Verge / Surge）

> 前置条件：已注册 [yydsflight.com](https://yydsflight.com) 并购买套餐，手上已有**订阅地址**。

## 方案一：Clash Verge（推荐，免费）

### 1. 下载安装
从 [Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev/releases) 下载 macOS 版：
- Apple 芯片（M1/M2/M3/M4）选 `aarch64.dmg`
- Intel 芯片选 `x64.dmg`

安装时若提示「无法打开」，到 **系统设置 → 隐私与安全性** 里点「仍要打开」。

### 2. 导入订阅
1. 打开 Clash Verge，点左侧「**订阅**」
2. 粘贴**订阅地址** → 点「导入」
3. 自动拉取全部节点

### 3. 连接
1. 「**代理**」页开启「系统代理」
2. 选一个低延迟节点（右键测延迟）
3. 菜单栏图标变化即成功

---

## 方案二：Surge（进阶，App Store 付费）

Surge 功能最强，适合进阶用户。

1. App Store 购买安装 Surge
2. 「**首页**」→「从 URL 添加配置」→ 粘贴订阅地址
3. 下载完成后「**策略组**」选一个节点
4. 「**出站模式**」设为「规则模式」，右上角开关打开

---

## 常见问题

- **首次打开提示"已损坏"？** macOS 对未签名应用的限制，系统设置里允许即可（见上）。
- **菜单栏图标是灰色？** 系统代理未开启，去「代理」页打开开关。
- **延迟都是超时？** 先「更新订阅」再测。

---

> 🌐 官网：**[https://yydsflight.com](https://yydsflight.com)** · 更多教程见 [README](../README.md)
