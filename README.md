# 🔋 BatteryGuard

**BatteryGuard** is a lightweight Windows desktop application that helps protect your laptop battery by providing **smart voice alerts** when you need to **plug in or unplug your charger**.  
It runs quietly in the **system tray**, starts automatically with Windows, and works in the background without interrupting your workflow.

---

## ✨ Features

- 🔊 **Voice alerts**
  - Alerts when battery is **low** and charger is not connected
  - Alerts when battery is **high** and charger is still plugged in
- 🔁 **Continuous reminders**
  - Keeps reminding you until action is taken
- 🖥 **System tray support**
  - Runs silently in the background
  - Close window without stopping the app
- 🚀 **Start with Windows**
  - Automatically launches on system startup
- ⚙ **Custom battery thresholds**
  - User-defined minimum and maximum battery levels
  - Settings are saved and restored automatically
- 🪶 **Lightweight & efficient**
  - Minimal CPU and memory usage

---

## 🛠 Built With

- **C#**
- **Windows Forms (.NET Framework)**
- **System.Speech.Synthesis** for voice alerts

---

## 📦 Installation

### Option 1: Installer (Recommended)
1. Download the published installer (`setup.exe`)
2. Run the installer
3. BatteryGuard will start automatically and appear in the system tray

### Option 2: Portable EXE
1. Download the `.exe` file
2. Run it directly (requires .NET Framework installed)

---

## 🧪 How It Works

- 🔻 If battery percentage drops **below minimum** while unplugged  
  → Voice alert: *“Battery is low. Please plug in the charger.”*

- 🔺 If battery percentage rises **above maximum** while plugged in  
  → Voice alert: *“Battery is full. Please unplug the charger.”*

Alerts repeat every few seconds until the correct action is taken.

---

## 📂 Settings Storage

Battery thresholds are saved automatically using Windows user settings and persist across restarts.

---

## 🔒 Privacy

BatteryGuard:
- ❌ Does NOT collect data
- ❌ Does NOT use the internet
- ✅ Runs entirely offline

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Open a Pull Request

---

## 📄 License

This project is open-source and available under the **MIT License**.

---

## 🙌 Acknowledgements

Built to help extend laptop battery life and promote healthy charging habits.

---

⭐ If you find this project useful, please consider giving it a **star** on GitHub!
