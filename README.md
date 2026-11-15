<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" alt="Gourav Kumar, co-founder and lead developer at Shimio" width="560">
</picture>

I'm the co-founder and lead developer of [Shimio](https://shimio.in), an online marketplace for the shops of Shimla's bazaars. I build the platform end to end: the storefront, seller tools, payments, shipping, the mobile app and the accounting behind merchant payouts.

Outside Shimio I build hardware around the ESP32: displays, sensors, NFC, IR, motors and battery packs, together with the firmware, apps and browser tools that run them.

## Shimio

[shimio.in](https://shimio.in) sells goods from Tibetan Market, Lakkar Bazaar, Lower Bazaar and Mall Road at fixed, GST-inclusive prices, with delivery in Shimla and across India.

- Custom WordPress theme on a WooCommerce back end (PHP, MySQL, JavaScript)
- Razorpay payments and Shiprocket shipping
- In-house accounting engine for GST and merchant payouts
- Customer app for Android and iOS in Flutter, with Riverpod, Google Sign-In and Firebase push notifications

The source code is private.

## Open-source projects

- **[ESP Widget](https://github.com/Joyboycoffee/Esp-Widget)**: A 240 × 240 desk display on an ESP32-C3 for time, weather, markets, notifications and media, paired with an Android app written in Kotlin and Jetpack Compose. Firmware and app share a versioned, CRC-checked BLE protocol that both sides test against the same vectors. [Web installer](https://joyboycoffee.github.io/Esp-Widget/)
- **[Spearhead Keychain](https://github.com/Joyboycoffee/Keychain)**: An ESP32-C3 keychain with a 1.3-inch IPS display that switches between animated faces, a clock, scrolling text and media streaming. It is controlled over Web Bluetooth from a dashboard that installs as a PWA. [Dashboard](https://joyboycoffee.github.io/Keychain/)
- **[Retro-Go on ESP32-S3](https://github.com/Joyboycoffee/Retro-Go-ESP32-S3)**: A handheld console built around an ESP32-S3 with a 2.4-inch display, I2S audio, microSD storage and 11 buttons, running the open-source Retro-Go emulator firmware. The repository documents the full pinout and builds the firmware with GitHub Actions.
- **[ESP32-C3 Video Streamer](https://github.com/Joyboycoffee/ESP32-C3-Video-Streamer)**: Streams video from a phone or PC to a small ESP32-C3 display over Wi-Fi, using WebSocket and UDP. It runs from a browser, a Windows app or a Python CLI. [Web app](https://joyboycoffee.github.io/ESP32-C3-Video-Streamer/)
- **[ESP32 BLE Wi-Fi Remote](https://github.com/Joyboycoffee/ESP32-BLE-WiFi-Remote)**: Turns an ESP32-C3 into a Bluetooth keyboard and mouse driven from a phone's browser, with a trackpad, gyro air mouse, hotkeys, media keys and over-the-air updates.

## Other builds

Projects I've built that aren't published yet.

- **NFC Command Deck**: A native Windows app in C++ (Win32 and GDI+) paired with an ESP32-C3 and RC522 reader. Tapping a card launches an app or game, plays a Spotify playlist, runs a script, sends a keyboard shortcut or locks the PC. It connects over USB serial or Wi-Fi, runs as a background service and uses about 10 MB of RAM.
- **Dual-boot handheld firmware**: A 16 MB image that boots either Retro-Go or a rebuilt Bruce firmware on the same ESP32-S3, with an IR transmitter and a remote-code library sorted by device type, from Indian DTH boxes and TVs to ACs and fans.
- **Bluetooth gamepad bridge**: An ESP32-C3 that pairs with a Bluetooth controller and forwards its input to the handheld over UART as framed packets.
- **Sim racing speedometer**: A salvaged motorcycle instrument cluster driven by an ESP32-C3, a VID29 stepper and an HT1621 LCD controller, with Python telemetry bridges for Forza Horizon, Euro Truck Simulator 2 and WRC. It runs on a 3S 18650 pack with a BMS.
- **PWM fan controller**: ESPHome firmware on an ESP-01 or ESP32 with a MOSFET circuit to drive fans that lack PWM input, and a WPF desktop app with fan curves and a tray icon.
- **Door sensor and proximity lock**: An ESP32-C3 that locks the PC when my phone's BLE beacon leaves range, watches a door with a hall-effect sensor, sends Telegram alerts and reports battery health.
- **Fan RPM and battery logger**: A hall-effect tachometer that also benchmarks battery discharge runs and logs them to flash, with a live web dashboard.
- **Dusk-to-dawn motion light**: An ESP32-C3 that switches a 230 V AC light through a relay using a PIR sensor and an LDR, with a web dashboard for calibration and manual override.
- **Desk clock for the Samsung Wave 525**: A full-screen Java ME clock that turns an old feature phone into a desk clock.

## Stack

- **Languages:** C, C++, Dart, Kotlin, PHP, JavaScript, TypeScript, Python, C#, Java, SQL, HTML, CSS
- **Web:** WordPress, WooCommerce, MySQL, Next.js, React, FastAPI, Flask, PWAs, Web Bluetooth, Web Serial
- **Mobile:** Flutter with Riverpod and go_router, Kotlin with Jetpack Compose and Glance, Capacitor
- **Desktop:** Win32 and GDI+ in C++, WPF on .NET, PyQt5, Tkinter, PyInstaller
- **Embedded:** ESP32, ESP32-C3, ESP32-S3, ESP8266, ESP-IDF, PlatformIO, Arduino, ESPHome, NimBLE, LovyanGFX, LittleFS
- **Hardware:** SPI and I2C displays, I2S audio, RC522 NFC, IR, PIR, hall-effect and light sensors, stepper motors, relays and MOSFETs, 18650 packs with BMS and TP4056 charging
- **Services:** Razorpay, Shiprocket, Firebase, Google Sign-In, Telegram bots, Hostinger
- **Tooling:** Git, GitHub Actions, esptool, Android Studio, VS Code

## Contact

- Email: [g.k.sroye@gmail.com](mailto:g.k.sroye@gmail.com)
- Instagram: [@go.ur.av](https://instagram.com/go.ur.av)
- Shimio: [shimio.in](https://shimio.in)

If something here helped you, you can [buy me a coffee](https://buymeacoffee.com/go.ur.av).

<details>
<summary>More links</summary>

[LinkedIn](https://www.linkedin.com/in/gouravkmrsroye/)

</details>
