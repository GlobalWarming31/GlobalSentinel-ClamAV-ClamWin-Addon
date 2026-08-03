# Global Sentinel

Global Sentinel is a lightweight, real-time protection interface for **ClamWin** and **ClamAV**. It bridges the gap by adding active background monitoring, automated scanning, and a sleek GUI to manage your open-source antivirus tools on Windows.

It monitors connected system drives, logs scan activities instantly, and features a customizable whitelist to bypass specific files or folders. Configure ClamWin/ClamAV scanner, database, quarantine, and FreshClam paths easily while managing automated startup right from the interface.

## 🚀 Features

* **Active Real-Time Protection:** Continuous background security monitoring for your system.
* **Multi-Drive Monitoring:** Selectively monitor `C:\`, `D:\`, `E:\`, and other connected system drives.
* **Sleek Configuration Management:** Easily map and browse paths for:
  * **ClamWin Scanner:** `clamscan.exe`
  * **FreshClam Path:** `freshclam.exe` (ClamAV)
  * **Virus Database:** Custom database and definition storage
  * **Quarantine Folder:** Isolated directory for flagged threats
* **Custom Whitelisting:** Quickly exclude trusted files or folders to bypass real-time scanning.
* **Live Activity Log:** Real-time feedback showing instant scanning results and clean file verifications.
* **Automation:** Optional "Start on Windows Bootup" toggle to ensure you are always protected.

## ⚙️ Configuration & Paths

To ensure Global Sentinel functions properly, verify your application paths match your system installation. Typical defaults:

* **Scanner:** `C:\Program Files (x86)\ClamWin\bin\clamscan.exe`
* **FreshClam:** `C:\Program Files\ClamAV\freshclam.exe`
* **Database:** `C:\ProgramData\.clamwin\db`
* **Quarantine:** `C:\ProgramData\.clamwin\quarantine`

## 🛠️ Installation & Setup

1. **Prerequisites:** Ensure you have both [ClamWin](https://clamwin.com/) and [ClamAV](https://www.clamav.net/) installed on your Windows system.
2. **Download:** Download the latest release from the [Releases](../../releases) tab.
3. **Launch:** Run the executable, configure your paths, check "Enable Real-Time Protection", and click **Save & Apply Settings**.

## 🔒 Integrity Verification

Verify the downloaded file using the following SHA-256 checksum:

```text
3F0614C0F4BF5F1C4466FA7B1FE594FA0370FA43C0D1D971D33A4A85CEB6BD92
```

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](../../issues).

## 📄 License

This project is licensed under the [MIT License](LICENSE).
