# 🛡️ DriverWatcher

> PowerShell script to **monitor and remove unauthorized drivers** — whitelists Microsoft, Realtek, Dolby, Intel, AMD, NVIDIA, MediaTek; removes all others.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🔍 **Driver Scan** | Uses `Win32_PnPSignedDriver` to list drivers |
| 📋 **Vendor Whitelist** | Microsoft, Realtek, Dolby, Intel, AMD, NVIDIA, MediaTek |
| 🗑️ **Force Remove** | `pnputil /delete-driver` for non-whitelisted drivers |
| ⏰ **Background Job** | Runs every 60 seconds |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10/11 |
| **PowerShell** | 5.1+ |
| **Privileges** | Administrator |

---

## 🚀 Usage

```powershell
# Run as Administrator
.\DriverWatcher.ps1
```

---

## ⚠️ Warning

Removing drivers can break hardware (printers, USB devices, etc.). Customize the whitelist before use. Create a restore point first.

---

<p align="center">
  <sub>🛡️ Gorstak Security Tooling</sub>
</p>
