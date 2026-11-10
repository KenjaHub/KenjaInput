# KenjaInput 隐私政策 / Privacy Policy

**最后更新 / Last updated: 2026-11-10**

---

## 中文

### 一句话版本

**KenjaInput 不收集、不传输、不分享任何用户数据。它甚至不联网。**

### 数据收集与使用

- **无账号**：应用不需要注册、登录，不关联任何身份。
- **无网络**：应用不含任何网络请求代码——不存在「上传」这个动作。
- **无统计**：不包含任何分析、统计、广告或追踪 SDK。
- **本地存储**：你的全部数据（输入法规则、快捷文字模板、图片、图文组合）
  仅保存在本机应用沙盒容器内（`~/Library/Containers/com.kofukuai.kenjainput/`），
  删除应用即删除全部数据。

### 权限说明

| 权限 | 用途 | 是否必需 |
|---|---|---|
| 辅助功能（Accessibility） | 向当前应用发送 ⌘V 粘贴事件，实现快捷模板插入；识别密码输入框以避免向其粘贴内容 | 仅快捷粘贴功能需要；按应用自动切换输入法**不需要**任何权限 |

应用**不会**读取你的键盘输入内容；辅助功能仅用于：（1）模拟一次 ⌘V 粘贴
你自己保存的模板内容；（2）判断当前焦点是否为密码框。

### 儿童隐私

应用不面向儿童收集任何信息——事实上它不收集任何人的任何信息。

### 政策变更

如政策发生变更，会在本页面更新并标注日期。

### 联系方式

如有任何问题：https://github.com/koihuang/KenjaInputSwitch/issues

---

## English

### The one-line version

**KenjaInput does not collect, transmit, or share any user data. It never
touches the network at all.**

### Data collection and use

- **No accounts**: no sign-up, no sign-in, no identity of any kind.
- **No network**: the app contains no networking code — "uploading" is
  not something it can do.
- **No analytics**: no analytics, advertising or tracking SDKs of any kind.
- **Local storage only**: all of your data (input-method rules, text
  snippets, images, mixed blocks) stays inside the app's sandbox container
  (`~/Library/Containers/com.kofukuai.kenjainput/`). Deleting the app
  deletes all of it.

### Permissions

| Permission | Purpose | Required? |
|---|---|---|
| Accessibility | Sends a ⌘V paste event to the frontmost app to insert your snippets; detects secure (password) fields to avoid pasting into them | Only for snippet pasting; per-app input-method switching needs **no** permission |

The app **never** reads your keyboard input. Accessibility is used solely
to (1) simulate a single ⌘V paste of content you saved yourself, and
(2) check whether the focused field is a secure text field.

### Children's privacy

The app collects no information from anyone — including children.

### Changes to this policy

If this policy changes, the change will be posted on this page with an
updated date.

### Contact

Questions: https://github.com/koihuang/KenjaInputSwitch/issues
