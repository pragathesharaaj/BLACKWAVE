# 📡 Black Wave – ESP32 Wi-Fi Sniffer

**Black Wave** is a lightweight, ESP32-based Wi-Fi sniffer that scans for nearby wireless networks and logs key information like SSID, MAC address, signal strength (RSSI), and channel. Built for ethical usage, it's ideal for wireless diagnostics, IoT testing, and learning about Wi-Fi networks.

---

## 🚀 Features

- Scans all nearby Wi-Fi networks
- Displays:
  - 📶 SSID (Network Name)
  - 🧭 BSSID (MAC Address)
  - 📡 RSSI (Signal Strength)
  - 🔁 Channel Number
- Runs on ESP32 with Arduino IDE
- Lightweight and fast
- Legal and safe for personal use

---

## 🛠️ Hardware Requirements

- ESP32 development board (e.g., ESP32 DevKit v1 or ESP32-S3)
- Micro-USB cable
- Arduino-compatible PC (Windows/Linux/macOS)

---

## 🧑‍💻 Installation

1. **Install Arduino IDE** – [Download here](https://www.arduino.cc/en/software)
2. **Install ESP32 Board Support**:
   - Go to `File > Preferences`
   - Add the following to *Additional Board URLs*:
     ```
     https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
     ```
   - Open `Tools > Board > Boards Manager`, search `ESP32`, and install it.
3. **Select Your ESP32 Board** under `Tools > Board`.
4. **Connect your ESP32** and select the correct port.
5. **Upload the Code** from `blackwave_sniffer.ino`.

---

## 🧪 Usage

1. Open the **Serial Monitor** at 115200 baud rate.
2. The ESP32 will scan and list all nearby Wi-Fi networks every 10 seconds.
3. You’ll see output like:

   ---

## ⚠️ Disclaimer

> **Black Wave is a legal and ethical Wi-Fi scanning tool.**  
> It does not send any deauthentication or jamming packets.  
> Use it only on your own network or with permission.  
> Do not modify this project for illegal purposes like Wi-Fi jamming or packet injection.
