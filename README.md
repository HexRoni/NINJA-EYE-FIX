# 🥷 NINJA EYE

### A Python-Based Educational Cybersecurity Toolkit

**NINJA EYE** is a Python-based command-line toolkit designed for learning basic cybersecurity, local network analysis, file integrity verification, and system security checks.

Developed by **Roni**, this project brings several useful diagnostic tools together in one terminal-based application.

## ✨ Features

- 🌐 **Network Analyzer** — Displays basic hostname and local IP information.
- 🔌 **Localhost Port Checker** — Checks TCP ports on the local machine.
- 🔐 **File Hash Calculator** — Calculates MD5, SHA-1, and SHA-256 file hashes.
- 📁 **File Permission Checker** — Inspects file permissions and highlights potentially unsafe settings.
- 🛡️ **Security Checks** — Checks selected environment settings, dependencies, and project files.
- 🧪 **Self-Test** — Runs basic checks on the application environment.
- 🖼️ **Image Metadata Analyzer** — Inspects supported image metadata.

## 🧰 Built With

- Python 3
- Python Standard Library
- Pillow
- TCP sockets
- File hashing algorithms

## 📋 Requirements

- Windows or a compatible Linux environment
- Python 3
- pip
- Project dependencies listed in `requirements.txt`

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/HexRoni/Ninja-eye.git
```

### 2. Open the Project Folder

```bash
cd Ninja-eye
```

### 3. Install Dependencies

**Windows PowerShell:**

```powershell
py -m pip install -r requirements.txt
```

**Linux:**

```bash
python3 -m pip install -r requirements.txt
```

### 4. Run NINJA EYE

**Windows:**

```powershell
py ninja_eye.py
```

**Linux:**

```bash
python3 ninja_eye.py
```

## 🖥️ Available Modules

| Module                  | Purpose                                    |
| ----------------------- | ------------------------------------------ |
| Network Analyzer        | Displays local network information         |
| Image Metadata Analyzer | Reads supported image metadata             |
| Localhost Port Checker  | Checks ports on the local machine          |
| File Hash Calculator    | Generates file hashes for integrity checks |
| File Permission Checker | Inspects file access permissions           |
| Security Checks         | Performs basic environment diagnostics     |

## 🔬 Educational Purpose

NINJA EYE demonstrates fundamental Python programming and defensive cybersecurity concepts, including:

- Network information gathering on the local device.
- TCP connection checks on localhost.
- Cryptographic file hashing.
- File permission inspection.
- Dependency and project environment validation.

## 🔒 Security and Privacy

NINJA EYE is intended for educational and authorized defensive use.

- Use the tool only on systems and files you own or have permission to inspect.
- The localhost port checker is intended for local testing.
- File hashes help verify integrity but do not independently prove that a file is safe.
- Basic security checks are not a replacement for a professional security audit.
- Never publish passwords, API keys, or other sensitive credentials.

## ⚠️ Limitations

- Available network information can vary by operating system.
- Some features require additional dependencies.
- Port-checking results do not establish whether a service is secure.
- The tool is an educational project, not a comprehensive vulnerability scanner.

## 🛣️ Future Improvements

- [x] Improve Windows and Linux compatibility.
- [ ] Expand automated testing.
- [x] Improve error handling and logging.
- [x] Add more diagnostic features.
- [x] Improve documentation and usability.

## 👨‍💻 Author

**Roni**

- **GitHub:** [@HexRoni](https://github.com/HexRoni)
- **Project:** NINJA EYE

Developed independently by Roni.

## © Copyright

Copyright © 2026 Roni. All rights reserved, subject to the project's selected license.

Please respect the author's work and the applicable license terms. Add an appropriate `LICENSE` file to define how others may use, modify, or redistribute this project.

## ⚖️ Disclaimer

This project is provided for educational and defensive cybersecurity purposes only. Users are responsible for ensuring that their activities comply with applicable laws and authorization requirements.

---

**NINJA EYE — Learn. Analyze. Secure.**

*Created by Roni | GitHub: HexRoni*
