# Windows 客户端配置教程（Clash Verge / v2rayN）

> 前置条件：已注册 [yydsflight.com](https://yydsflight.com) 并购买套餐，手上已有**订阅地址**（控制台可见）。

## 方案一：Clash Verge（推荐）

Clash Verge 是 Windows 上体验最好的机场客户端之一，界面清爽、更新节点快。

### 1. 下载安装
从官方 Release 下载：[Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev/releases)，选 `Clash.Verge_x.x.x_x64-setup.exe` 安装。

### 2. 导入订阅
1. 打开 Clash Verge，左侧点「**订阅**」
2. 顶部「订阅文件」卡片，粘贴你的**订阅地址**
3. 点「导入」，客户端自动拉取全部节点

### 3. 连接
1. 回到「**代理**」页，点右上角「系统代理」开启
2. 在节点列表选一个**延迟低**的节点（右键测延迟，选数字最小的）
3. 状态栏图标变绿即成功

### 4. 验证
浏览器打开 google.com 能访问 = 配置成功。

---

## 方案二：v2rayN（经典老牌）

### 1. 下载
从 [v2rayN Release](https://github.com/2dust/v2rayN/releases) 下载 `v2rayN-windows-64.zip`，解压运行 `v2rayN.exe`。

### 2. 导入订阅
1. 顶部菜单「**订阅分组**」→「订阅分组设置」
2. 粘贴订阅地址 → 确定
3. 「**订阅分组**」→「更新全部订阅（不通过代理）」

### 3. 连接
1. 系统托盘右键 v2rayN 图标 → 「系统代理」→「自动配置系统代理」
2. 双击一个节点设为活动节点（或右键「设为活动服务器」）
3. 图标变绿即成功

---

## 常见问题

- **更新订阅报错？** 检查订阅地址是否复制完整（前后无空格），网络能正常打开 yydsflight.com。
- **节点延迟都是超时？** 换「不通过代理」更新一次；仍不行在官网提工单。
- **关闭软件后网络断？** 正常现象（系统代理还开着），退出前先关闭「系统代理」或直接退出软件即可恢复。

---

> 🌐 官网：**[https://yydsflight.com](https://yydsflight.com)** · 更多教程见 [README](../README.md)
