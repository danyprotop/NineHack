# 🛴 Ninehack 

<p align="center">
  <img src="https://shields.io" alt="Release">
  <img src="https://shields.io" alt="Stars">
  <img src="https://shields.io" alt="License">
</p>

---

## 📝 Description

**Ninehack** is an advanced Android application (APK) designed for monitoring, configuring, and managing **Ninebot** electric scooters. It provides users with deep insights into their hardware, custom tuning, and an improved riding experience beyond factory limitations.

> ⚠️ **Disclaimer:** This project is intended for educational and personal utility purposes only. Flashing custom firmware or changing factory settings may void your warranty or violate local laws. Use it at your own risk.

---

## ✨ Features

📱 **User-Friendly Dashboard**
* Real-time telemetry tracking (speed, battery cells voltage, mileage, power output).
* Sleek and modern Android UI tailored for one-handed operation while riding.

⚙️ **Advanced Tweaking & Tuning**
* Speed limit adjustments (depending on the scooter model and firmware version).
* Cruise control, KERS (recuperation), and startup speed configurations.

🔍 **Diagnostics & Battery Health**
* Detailed view of individual battery cell voltages.
* Error code reading and clearing.
* Estimated real-world range calculator based on riding style.

---

## 🛠️ Built With

* **Kotlin / Java** — Native Android development.
* **Android SDK** — Core framework and Bluetooth Low Energy (BLE) API.
* **Jetpack Compose** — Modern UI toolkit for building native user interfaces.
* **Gradle** — Build automation system.

---

## 🚀 Installation & Usage

### Method 1: Download Pre-built APK (Recommended)
1. Go to the [Releases](https://github.com) page.
2. Download the latest `.apk` file.
3. Transfer it to your Android device and install it (make sure to allow installation from unknown sources).
4. Turn on your scooter, enable Bluetooth on your phone, open Ninehack, and connect!

### Method 2: Build from Source
To compile the APK yourself, clone this repository and open it in **Android Studio**:

```bash
# Clone the repository
git clone https://github.com

# Open the project in Android Studio and build via Gradle:
./gradlew assembleDebug
```
The output APK will be located in `app/build/outputs/apk/debug/`.

---

## 🤝 Contributing

Contributions, bug reports, and feature requests are welcome! 
1. **Fork** the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a **Pull Request**.

---

## 📄 License

Distributed under the **Apache License 2.0**. See the [LICENSE](LICENSE) file for more details.

---

<p align="center">
  Developed with ❤️ by <a href="https://github.com">danyprotop</a>
</p>
