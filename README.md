安卓本地逆向 MCP 网关

# 清风 QingFeng

本地逆向工程 MCP 网关（SOMCP v11）

运行在 Android 设备上，将 apktool / jadx / rizin / frida / blutter
聚合为统一 MCP 端点，让 AI 直接分析设备上的 .so / .apk。

- SO 分析：so_open → analyze_* / edit_* → build_so
- APK 工具：解码、smali 回编、签名、对比、脱壳
- 沙箱测试：安装 / 运行 / 抓日志 / 看门狗
- 双通道提权：Shizuku + Root
- 内置工具链：apktool、jadx、rizin、frida、blutter、Node.js、Python
- Cloudflared 内网穿透

许可证：GPL-3.0
作者：白时（QQ：3774724272)

QQ群:(1103502649)

![mm_reward_qrcode_1786567756779.png......]()

<图片 宽度="1037" 高度="1037" 替代=“mm_reward_qrcode_1786567756779” src="https://github.com/user-attachments/assets/89a1720c-40b3-4dc2-99d7-a168ad298531" />
