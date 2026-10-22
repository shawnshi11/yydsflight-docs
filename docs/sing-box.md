# sing-box 通用客户端配置教程（全平台）

> 前置条件：已注册 [yydsflight.com](https://yydsflight.com) 并购买套餐，手上已有**订阅地址**。

sing-box 是通用代理内核，官方提供全平台图形客户端，适合喜欢折腾或想一套配置跑所有设备的用户。

---

## 下载客户端

从官方 Release 下载对应平台版本：[sing-box Release](https://github.com/SagerNet/sing-box/releases)

| 平台 | 文件 |
|---|---|
| Windows | `sing-box-x.x.x-windows-amd64.zip` |
| macOS | `sing-box-x.x.x-darwin-universal.zip` |
| Android | `SFA-x.x.x-universal.apk`（或应用市场 sing-box） |
| iOS | App Store 搜索 sing-box（海外 Apple ID） |

---

## 图形客户端配置（Android/桌面通用）

1. 打开客户端，进入「**Profiles（配置）**」
2. 点 `+` → 「**Import from URL / 从 URL 导入**」
3. 粘贴你的**订阅地址**，保存并选中启用
4. 回到主界面选一个低延迟节点
5. 打开代理开关，允许系统 VPN 配置

---

## 命令行/内核模式（进阶）

桌面端也可以只用内核 + 订阅转配置文件：

```bash
# 下载订阅并转为 sing-box 配置（需订阅地址）
curl -L "你的订阅地址" -o sub.json
sing-box check -c sub.json
sing-box run -c sub.json
```

> 订阅地址里已包含节点信息，sing-box 可直接读取，无需手动填服务器参数。

---

## 常见问题

- **导入后没有节点？** 检查订阅地址是否完整，客户端里手动「更新」一次。
- **sing-box 与 Clash 配置能通用吗？** 订阅地址是通用的，但配置格式不同，各客户端各自导入即可。

---

> 🌐 官网：**[https://yydsflight.com](https://yydsflight.com)** · 更多教程见 [README](../README.md)
