
# 🛠️ Snigdha OS Calamares Configuration

This repository contains the **Calamares Configuration** files tailored for **Snigdha OS**, enabling a seamless and user-friendly installation experience. Calamares is a powerful, adaptable, and customizable installer framework widely used in Linux distributions. 

<p align="center">
  <img src="https://github.com/user-attachments/assets/01e5b94f-354d-4e9c-a894-af222d0b24cf" alt="Snigdha OS Logo" width="300">
</p>

<div align="center">
  <img alt="MIT License" src="https://img.shields.io/badge/license-MIT-754ffe?style=for-the-badge&logo=book&logoColor=92fe9d">
  <img alt="Calamares Version" src="https://img.shields.io/badge/calamares-3.x-754ffe?style=for-the-badge&logo=linux&logoColor=92fe9d">
</div>

---

## 📜 Overview

This configuration is specifically optimized for the **Snigdha OS Arctic V** release, ensuring:
- **Simplified Installation Process** with an intuitive UI.
- **Support for Custom Partitioning** to suit diverse user needs.
- **Preloaded Setup Scripts** for environment initialization and optimization.
- **Snigdha OS Branding** for a cohesive and professional look.

---

## 📁 Repository Structure

```plaintext
.
├── branding/
│   ├── logo.png         # Snigdha OS branding assets
│   ├── stylesheet.qss   # Custom styles for the installer UI
│   └── translations/    # Language translations for installer
├── modules/
│   ├── partition.conf   # Partitioning configuration
│   ├── locale.conf      # Localization and language settings
│   ├── users.conf       # User setup configurations
│   └── shellprocess/    # Custom post-install scripts
├── settings.conf        # Main configuration file for Calamares
└── README.md            # Documentation
```

---

## ⚙️ Features

- **🖼️ Custom Branding**: The installer features Snigdha OS logos, colors, and themes for a unified experience.
- **🌍 Localization Support**: Multilingual installer with pre-configured translations.
- **📦 Package Installation**: Automated installation of essential packages.
- **🔒 Secure Defaults**: Implements secure partitioning and configuration options by default.
- **🛠️ Post-Install Scripts**: Runs post-installation scripts to finalize the setup, applying system optimizations and branding.

---

## 🛠️ How to Use

### Prerequisites:
- Ensure **Calamares** is installed on the target system.
- Clone this repository:
  ```bash
  git clone https://github.com/Snigdha-OS/snigdhaos-calamares-config.git
  ```
- Install dependencies for Calamares:
  ```bash
  sudo pacman -S calamares qt5-base
  ```

### Steps:
1. **Configure Calamares:**
   Copy the contents of this repository to your Calamares configuration directory:
   ```bash
   sudo cp -r snigdhaos-calamares-config/* /etc/calamares/
   ```
2. **Edit Settings:**
   Modify the `settings.conf` file to reflect your installation preferences if needed.
3. **Run Calamares Installer:**
   Launch Calamares with the custom configuration:
   ```bash
   sudo calamares
   ```

---

## 📦 Development

### Customizing Branding:
- Update the **branding/logo.png** and **stylesheet.qss** files to adjust the UI.
- Add additional translations under the `branding/translations/` folder.

### Adding Modules:
- New modules can be added to the `modules/` directory. Refer to the [Calamares Documentation](https://calamares.io/docs/modules/) for more details.

---

## 🛡️ License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

## 👨‍💻 Contributors

| Contributor       | Role                      | Contact                                                                                       |
|-------------------|---------------------------|----------------------------------------------------------------------------------------------|
| **@eshanized**    | Lead Developer            | [GitHub](https://github.com/eshanized)                                                      |
| **@alokified**    | Web Infrastructure | [GitHub](https://github.com/alokified)                                                      |
| **@utkrshift**    | UI/UX Designer            | [GitHub](https://github.com/utkrshift)                                                      |

---

## 🌟 Acknowledgments

Special thanks to the **Snigdha OS Team** and our sponsors **Tonmoy Infrastructure** and **IXH International Co.** for their support in creating a modern and efficient Linux experience.

---

## 🔗 Useful Links

- [Snigdha OS Official Website](https://snigdhaos.org)
- [Calamares Documentation](https://calamares.io/docs/)
- [Snigdha OS Arctic Repository](https://github.com/Snigdha-OS/snigdhaos-arctic)
