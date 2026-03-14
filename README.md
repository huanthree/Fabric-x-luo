## Maohi Mod
这是一个用于 Minecraft Fabric 服务器的 Maohi 代理 Mod，支持多种协议的代理，自动构建。

### **使用说明**
1：fork本项目
2：在Actions菜单允许 `I understand my workflows, go ahead and enable them` 按钮
3: 在仓库 Settings → Secrets and variables → Actions 里添加以下 Secrets
4: 点击 Actions 手动触发构建
5: 等待2分钟后，在右边的Release里的Latest Build里下载jar结尾的文件上传至服务器mods文件夹启动即可

### **相关 Secrets 说明**
```
UUID                                       # 默认UUID
NEZHA_SERVER                               # Nezha服务器地址, v1: nezha.xxx.com:8008
NEZHA_KEY                                  # Nezha agent密钥,面板后台安装命令里获取
ARGO_PORT                                  # Argo隧道端口
ARGO_DOMAIN                                # Argo固定隧道域名
ARGO_AUTH                                  # Argo固定隧道密钥
HY2_PORT                                   # HY2端口，留空不启用
S5_PORT                                    # Socks5端口，留空不启用
CFIP                                       # 优选域名或优选IP
CFPORT                                     # 优选域名或优选ip对应的端口，默认443
CHAT_ID                                    # Telegram Chat ID，留空不推送
BOT_TOKEN                                  # Telegram Bot Token，留空不推送
NAME                                       # 节点名称
```
