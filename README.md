# shadowrocket-config

Shadowrocket（小火箭）个人分流配置的托管仓库。配置文件由 Remy 维护推送，使用者在 App 里点「更新」即可同步最新版。

## 配置文件

- 文件：`Shadowrocket.conf`（五合一整合版 · 七区制分流）
- 直链（导入和更新用同一条）：

  https://raw.githubusercontent.com/arvinlu888/shadowrocket-config/main/Shadowrocket.conf

## 导入方法（只需一次）

小火箭 → 配置 → 右上角 + → 从 URL 导入 → 粘贴上面的直链。

以后配置有更新时，在配置页对这条配置点「更新」即可，不用重新导入。

## 分区（组名 = 实际出口地）

- 美国（风控）：PayPal / WhatsApp / Tello 等风控敏感服务
- 美国：Claude / Meta 全家桶等
- 日本 / 台湾 / 韩国 / 香港：各自地区的专属业务
- 新加坡：其余境外流量的默认出口（兜底）
- 中国大陆：直连

规则集为远程引用，会自动保持最新；本仓库只托管分流结构本身。文件不含任何节点、订阅或密码信息。
