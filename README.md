# SMSIndex 📱

**SMSIndex** is a privacy-first Android app that organizes your SMS inbox into smart, searchable folders — all processed 100% locally.

### ✨ Features

- 🔐 Local-only message processing (no cloud, no tracking)
- 📂 Smart message folders:
  - Unread Messages
  - Last Message from Sender
  - Last Message from You
  - Saved Numbers
  - Unsaved Numbers
  - Short Codes (e.g., 72975, 67987)
- 🔄 Tap a message to open it in your default SMS app
- 🔁 Auto-refresh on resume (with throttling)
- 🔃 Manual refresh via button
- 🧠 Intelligent refresh — only reloads if messages actually changed

### 🛠 Built With

- Kotlin
- Android SDK
- `TabLayout` + `ViewPager2`
- Content Resolver (SMS & Contacts access)

### 🔧 Permissions Used

- `READ_SMS`
- `RECEIVE_SMS`
- `READ_CONTACTS`

> SMSIndex does **not** store, transmit, or process any message data outside of your device.

### 🚀 Getting Started

1. Clone this repo or download the ZIP
2. Open in Android Studio
3. Grant SMS & Contacts permissions when prompted
4. Build & run on your Android device

---

### 💡 Roadmap (Ideas)

- Message search
- Favorite/starred messages
- Custom folder creation
- Dark mode
- AI-powered message tagging (local)

---

### 📄 License

MIT License – see [LICENSE](./LICENSE) for details.
