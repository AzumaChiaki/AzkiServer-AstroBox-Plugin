# Azki Server · AstroBox 插件

Azki 系列官方 AstroBox 插件，用来激活并安装 Azki 资源（表盘与快应用）。

- 在 AstroBox 资源页点「安装」时，由本插件接管安装：已获授权的资源直接加入安装队列，未激活时跳到插件页激活。
- 直接打开插件：查看当前手表已获授权的资源并安装，或用**兑换码**或**爱发电订单号**（二选一）激活新资源。

本仓库只存放发布到 AstroBox 插件市场的构建产物，供插件市场索引读取：

| 路径 | 说明 |
|---|---|
| `index.txt` | 插件目录列表 |
| `dist/manifest.json` | 插件清单 |
| `dist/azvf_astro_plugin.wasm` | 插件本体（WASI Preview 2，API Level 4） |
| `dist/icon.png` | 图标 |
| `dist/AzkiServer-*.abp` | 可直接拖进 AstroBox 安装的安装包 |

推荐从 AstroBox 插件市场安装。插件会向 Azki 服务发送手表序列号、型号等信息用于授权核验，首次使用时会弹出数据使用说明，同意后才会核销或安装。

© AzumaChiaki. All rights reserved.
