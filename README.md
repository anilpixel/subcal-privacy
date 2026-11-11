# Privacy Policy / 隐私政策 — SubCal

- **Application**: SubCal (订阅日历)
- **Package ID**: `com.kiri.limited.subcal`
- **Developer**: Kiri Limited (`anilpixel`)
- **Effective Date / 生效日期**: November 10, 2026

## English

**SubCal** (`com.kiri.limited.subcal`) is built with a strict local-first privacy architecture:

1. **On-Device Storage Only**: All subscription entries, prices, billing dates, payment channel labels, and custom exchange rates are stored exclusively on your device (`SharedPreferences`). We do not operate backend servers that collect your subscription ledger.
2. **Network Access (`android.permission.INTERNET`)**: Used strictly over HTTPS to fetch public foreign-exchange reference rates when you request a live rate refresh. No personal or device identifiers are transmitted.
3. **Local Notifications (`android.permission.POST_NOTIFICATIONS`)**: Used solely by on-device Android `WorkManager` tasks to notify you ahead of upcoming subscription renewal dates.
4. **No Advertising ID, Analytics, or Data Sharing**: SubCal does not access or use the Android Advertising ID (`AD_ID`), and contains no advertising SDKs, third-party trackers, or account sign-ups. We do not collect, sell, or share personal data.
5. **Data Deletion**: You may delete individual subscriptions inside the app at any time, or clear app storage / uninstall the app to permanently erase all local data.

**Contact**: [eziosyanse@gmail.com](mailto:eziosyanse@gmail.com) or [GitHub Issues](https://github.com/anilpixel/subcal-privacy/issues)

---

## 简体中文

**SubCal（订阅日历）**（`com.kiri.limited.subcal`）高度重视用户的个人隐私与数据安全：

1. **纯本地存储**：您录入的所有订阅项目、金额、扣款日期、扣款渠道备注及自定义汇率均仅保存在您的设备本地存储（`SharedPreferences`）中，不会上传至开发者服务器。
2. **网络访问说明（`android.permission.INTERNET`）**：仅当您主动点击更新实时汇率时，应用会通过 HTTPS 向公开汇率接口发起不含任何个人身份信息的标准汇率查询请求。
3. **通知提醒说明（`android.permission.POST_NOTIFICATIONS`）**：仅用于在本地通过系统 `WorkManager` 定时计算即将到期的订阅项目并向您发送设备本地续费通知。
4. **不使用广告 ID 与第三方追踪**：本应用不读取、不使用 Android 广告 ID（`AD_ID`），不包含任何广告 SDK、行为分析追踪器或账号注册要求，也不会收集、出售或共享任何个人数据。
5. **数据删除**：您可随时在应用内删除任意订阅记录，或通过系统设置清除应用数据 / 卸载应用以彻底移除全部本地数据。

**联系方式**：[eziosyanse@gmail.com](mailto:eziosyanse@gmail.com) 或 [GitHub Issues](https://github.com/anilpixel/subcal-privacy/issues)
