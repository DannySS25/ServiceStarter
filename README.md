# 🛠️ Windows Service Starter
**Developed by [screenersync](https://screenersync.com)**

A lightweight, high-performance C++ utility designed to quickly enable and start essential Windows services that are often disabled by optimization scripts or manual configurations.

## 🚀 Features
* **Menu-Driven Interface:** Simple numeric selection to manage services.
* **Automatic Config:** Switches services from 'Disabled' to 'Automatic' start type.
* **Service Support:**
    * **EventLog:** Essential for system logging and app stability.
    * **SysMain:** Improves system responsiveness and app launch speeds.
    * **DiagTrack:** Restores Telemetry and functional data services.
    * **DPS:** Diagnostic Policy Service for troubleshooting.
    * **PcaSvc:** Program Compatibility Assistant support.

## 📋 Requirements
* **Windows 10 or 11**
* **Administrator Privileges:** Modifying system services requires elevated permissions.

## 🛠️ Usage
1.  Download the `Service Starter.exe`.
2.  **Right-click** the file and select **Run as Administrator**.
3.  Choose the service you wish to enable by pressing the corresponding number (`1-5`).
4.  The tool will update the startup type to **Automatic** and attempt to start the service immediately.

## ⚠️ Important Note
This tool is provided as-is. Enabling services like `DiagTrack` (Telemetry) may reverse privacy-focused "debloat" settings. Only enable services you specifically need for your workflow.

## 🔗 Credits
Created and maintained by **screenersync**. 
Visit us at [screenersync.com](https://screenersync.com) for more tools and updates.

---
© 2026 screenersync. All rights reserved.
