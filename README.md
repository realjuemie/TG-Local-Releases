# TG Local Releases

这是 TG Local Android 的官方二进制发布仓库，仅提供 APK、更新清单和校验和，不包含应用源代码。

TG Local 完全免费。如果你通过其他渠道付费获取，请尽快自行申请退款。

请前往 [Releases](https://github.com/realjuemie/TG-Local-Releases/releases/latest) 下载：

- `arm64-v8a`：绝大多数现代安卓手机
- `armeabi-v7a`：较旧的 32 位 ARM 设备
- `x86_64` / `x86`：安卓模拟器或对应设备
- `universal`：不确定架构时使用

应用内更新通过根目录的 `latest.json` 选择本机 ABI 对应的 APK，并在无法匹配时回退通用版。
