# 隐私政策（Privacy Policy）

> 应用名称：彩票助手（HarmonyOS）
> 包名：`com.enderstudio.lotteryassistant`
> 版本：1.0.0　生效日期：2026-10-30
> 本文件同时用于应用市场「隐私政策」填写与审核材料引用；应用内「关于 → 合规声明」有等价简述。

## 1. 我们收集哪些信息

**本应用不收集、不上传任何个人信息。**

- 不申请通讯录、相册、文件、位置、麦克风、摄像头、电话、短信等任何敏感权限；
- 不采集设备标识符（IMEI / OAID / Android ID / SN 等）、MAC 地址、剪贴板内容；
- 不要求注册账号，不收集手机号、邮箱、身份证等身份信息；
- 不接入广告 SDK、第三方统计 SDK、崩溃上报 SDK。

## 2. 联网与数据用途

应用申请的唯一权限是 `ohos.permission.INTERNET`，**仅用于拉取公开开奖历史数据**：

- 数据来源：中国福彩网（cwl.gov.cn）、中彩网（zhcw.com）、中国体彩网（sporttery.cn）等公开页面；
- 请求内容：仅包含彩种、页码等公开参数，无任何用户标识或行为上报；
- 请求不携带 Cookie 中的用户信息，服务端无法据此识别个人。

## 3. 本地数据

以下数据**仅存储在本机应用沙箱内的 SQLite 数据库**（`lottery.db`），不会上传：

| 数据 | 用途 | 是否可删除 |
| --- | --- | --- |
| 开奖历史（公开数据副本） | 统计与走势展示 | 可（清除应用数据） |
| 选号方案（号码篮） | 本地记录 | 可（号码篮内删除/清空） |
| 我的购彩记录（手动录入） | 本地记账 | 可（记录页删除） |
| 界面偏好（彩种/窗口） | 记住上次选择 | 可（内存态，退出即重置） |

卸载应用或清除应用数据即全部删除，我们不保留任何副本。

## 4. 未成年人保护

本应用内容涉及彩票历史数据统计，**未满 18 周岁禁止购彩**，应用首页与关于页常驻该提示。

## 5. 免责声明

本应用仅提供历史开奖数据的统计分析与趣味选号工具：

- **不提供任何购彩、支付、兑奖服务**；
- **不承诺任何中奖结果**，选号结果由随机算法生成，仅供娱乐参考；
- 开奖数据以官方公布为准，若因数据源变动导致显示差异，以官方信息为准。

## 6. 隐私政策的变更

若后续版本新增需要收集信息的功能（当前无此计划），将在应用内显著位置提示并更新本政策，且遵循「最小必要」原则。

## 7. 联系方式

如对本政策有疑问，可通过应用市场页面的开发者联系方式反馈。

---

# Privacy Policy (English summary)

This app collects **no personal data**. The only permission is `INTERNET`, used solely to fetch
public lottery draw history from official public pages. Draw history copies, saved number
tickets and manually entered purchase records are stored **locally in the app sandbox SQLite
database** and are never uploaded. No ads, no analytics, no crash-reporting SDKs, no account
system. Uninstalling the app removes all local data. The app does not sell, pay for, or redeem
lottery tickets and does not promise any winning outcome. Lottery purchase is prohibited for
people under 18.
