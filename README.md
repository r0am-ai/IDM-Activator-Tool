# IDM Activation Script

<div align="center">

![Version](https://img.shields.io/badge/Version-1.2-blue)
![License](https://img.shields.io/badge/License-GPL--3.0-green)
![Platform](https://img.shields.io/badge/Platform-Windows-orange)

**Redesigned by INNO CYBER Community**

*A powerful script to activate and manage Internet Download Manager (IDM)*

</div>

---

## 🌟 About

The **IDM Activation Script** has been redesigned and enhanced by the **INNO CYBER** community to provide a seamless experience for managing your IDM installation. This script offers multiple functionalities including activation, trial freezing, and reset capabilities.

### ✨ Features

- 🔒 **Activate IDM** - Full activation of Internet Download Manager
- ❄️ **Freeze Trial** - Freeze the 30-day trial period indefinitely
- 🔄 **Reset Activation** - Reset activation and trial to start fresh
- 📥 **Download IDM** - Direct link to download the latest IDM version
- 🛠️ **Easy to Use** - Interactive menu-driven interface with colorful display

---

## 🎨 Redesign Highlights

This version has been completely redesigned by **M.Sabir Ali**, founder of the **INNO CYBER** community, featuring:

- ✅ Modern and professional user interface
- ✅ Color-coded menu for better visibility
- ✅ Enhanced error handling
- ✅ Improved user experience
- ✅ Clean and organized code structure

---

## 📋 Requirements

- Windows 7/8/8.1/10/11
- Internet Download Manager installed
- Administrator privileges

---

## 🚀 How to Use

### Method 1: Interactive Mode (Recommended)

1. Right-click on `IAS.cmd`
2. Select **"Run as administrator"**
3. Choose your desired option from the menu:
   - `[1]` Freeze Trial
   - `[2]` Activate
   - `[3]` Reset Activation / Trial
   - `[4]` Download IDM
   - `[5]` Help
   - `[0]` Exit

### Method 2: Command Line Parameters

You can run the script with parameters for unattended mode:

```batch
# Activate IDM
IAS.cmd /act

# Freeze Trial
IAS.cmd /frz

# Reset Activation
IAS.cmd /res
```

### Method 3: Edit Script

Open `IAS.cmd` in a text editor and change the values:

```batch
set _activate=1   :: To activate
set _freeze=1     :: To freeze trial
set _reset=1      :: To reset
```

---

## ⚙️ Options Explained

### 1️⃣ Freeze Trial
Freezes the IDM 30-day trial period, allowing you to use it indefinitely without purchasing.

### 2️⃣ Activate
Fully activates Internet Download Manager with permanent registration.

### 3️⃣ Reset Activation / Trial
Removes all activation and trial data, allowing you to start fresh.

### 4️⃣ Download IDM
Opens the official IDM download page in your browser.

### 5️⃣ Help
Opens the documentation and troubleshooting guide.

---

## 🛡️ Important Notes

> **⚠️ Disclaimer:** This script is for educational purposes only. Please support the developers by purchasing a legitimate license if you use IDM regularly.

- This script is **NOT working with the latest IDM versions** (as indicated in the menu)
- Always run the script as **Administrator**
- Make sure the **Null service** is running for proper functionality
- The script automatically handles both x64 and x86 systems

---

## 🔧 Troubleshooting

### Script closes immediately
- Make sure you're running as Administrator
- Check if antivirus is blocking the script
- Ensure the file has proper line endings (CRLF for Windows)

### Null service error
If you see "Null service is not running":
```batch
sc config Null start= demand
sc start Null
```

### Colors not displaying
- Update to Windows 10 build 10586 or later
- Enable legacy console mode if needed

---

## 📞 Contact & Support

**Developer:** M.Sabir Ali  
**Community:** INNO CYBER  
**Email:** lionh2682@gmail.com  
**Website:** http://innocyber.free.nf/  
**GitHub:** https://github.com/Sabir555S

---

## 📜 Version History

### Version 1.2 (Current)
- ✨ Redesigned UI with colorful interface
- ✨ Added INNO CYBER branding
- ✨ Improved menu structure
- ✨ Enhanced error handling
- ✨ Better documentation

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions or improvements:

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](https://github.com/Sabir555S/IDM-Activator-Tool/blob/main/LICENSE) file for details.

---

<div align="center">

### 💻 Made with ❤️ by INNO CYBER Community

**M.Sabir Ali - Founder**

*Empowering users with innovative solutions*

---

⭐ If you find this useful, please consider giving it a star!

</div>
