# 💎 Project Onyx Kernel

**Project Onyx** is a next-generation custom kernel for the **Samsung Galaxy Tab A7 (SM-T505 / gta4l)**. Designed for stability, performance, and intelligence.

This repository hosts the automated CI/CD workflow to build the kernel using **GitHub Actions**, ensuring a clean and up-to-date build environment every time.

---

### 🚀 Key Features

* **⚡ Proton Clang Compilation:** Built with the latest Proton Clang toolchain for maximum efficiency and speed.
* **🧠 Intelligent Installer:** Features a "Smart System Scan" that verifies OS integrity before flashing to prevent bootloops.
* **🏎️ Performance Tuned:**
    * **GPU Boost:** Adreno Idler & Boost enabled for better gaming performance.
    * **ZRAM Optimization:** LZ4 compression enabled for faster multitasking.
    * **Networking:** WireGuard VPN support + TTL Target fix.
* **🛡️ Security:**
    * **Permissive Mode:** Enabled by default for broad ROM compatibility (GSI/LineageOS).
    * **Samsung Knox Removed:** Defex, RKP, and Tima disabled to allow custom booting.
* **🎨 Onyx UI:** A clean, professional, and minimal installation interface in TWRP.

---

### 🛠️ How to Build

1.  Fork this repository.
2.  Go to the **Actions** tab.
3.  Select **"💎 PROJECT ONYX: Smart & Clean Builder"**.
4.  Click **Run workflow**.
5.  Wait for the build to finish and download the `Project-Onyx-Smart.zip` artifact.

---

### 📱 Compatibility

* **Device:** Samsung Galaxy Tab A7 10.4 (2020) - SM-T505
* **Chipset:** Snapdragon 662 (SM6115)
* **OS Support:** Android 11, 12, 13 (GSI & LineageOS supported)

---

### 📜 Credits

* **Kernel Source:** LineageOS Team
* **Toolchain:** kdrag0n (Proton Clang)
* **AnyKernel3:** osm0sis
* **Maintainer:** Joe (El Osta)
