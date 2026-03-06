# 🐍 CracksTheCodes

### Decompiled Python Code Collection by [@AtomixClub](https://github.com/AtomixClub)

Welcome to **CracksTheCodes** — a curated archive of reverse-engineered Python applications, scripts, and compiled bytecode. Whether you're a security researcher, malware analyst, or just curious about how Python programs work under the hood, this repository is for you.

> ⚠️ **Disclaimer**: This repository is intended for educational and research purposes only. Please respect intellectual property and only decompile code you have permission to analyze.

---

## 👨‍💻 About the Creator

**AtomixClub** is a reverse engineering enthusiast and Python security researcher passionate about understanding how software works at its core. This collection represents countless hours of decompilation, analysis, and documentation.

[![GitHub](https://img.shields.io/badge/AtomixClub-181717?style=for-the-badge&logo=github)](https://github.com/AtomixClub)
[![Twitter](https://img.shields.io/badge/@AtomixClub-000000?style=for-the-badge&logo=x)](https://x.com/AtomixClub)
[![Telegram](https://img.shields.io/badge/AtomixClubCommunity-0088cc?style=for-the-badge&logo=telegram&logoColor=ffffff)](https://t.me/AtomixClubCommunity)

---

## 🐍 What's Inside?

This repository contains decompiled source code from various Python formats, including:

- 📦 **Compiled Python Bytecode** – `.pyc` files from Python 2.7 to 3.11+
- 🔒 **PyInstaller Executables** – Decompiled standalone Windows/Linux/macOS apps
- 🥧 **Py2EXE & Py2APP** – Recovered source from packaged applications
- 📱 **Python-for-Android** – Kivy, BeeWare, and other mobile Python apps
- 🕸️ **Obfuscated Python** – Deobfuscated and cleaned source code
- 🧩 **Python Modules** – Extracted from various sources and platforms

---

## 🛠️ Tools Used

The decompilation process relies on a variety of specialized Python reverse engineering tools:

| Tool | Purpose |
|------|---------|
| **uncompyle6 / decompyle3** | Decompile Python bytecode (Python 2.7-3.8) |
| **pycdc** (Python Bytecode Decompiler) | Modern decompiler supporting Python 3.9+ |
| **pyinstxtractor** | Extract PyInstaller packages |
| **pyi-archive_viewer** | Explore PyInstaller archives |
| **unpy2exe** | Decompile py2exe executables |
| **pyREtic** | Dynamic analysis for obfuscated Python |
| **xdis** | Cross-version Python bytecode disassembler |
| **🧠 Brain** | The tool that actually does the work when all the automated ones fail |

---

## ⚠️ Important Note on Decompilation Results

**Not all files can be perfectly restored!**

Due to limitations in decompilation tools (uncompyle6, pycdc, etc.) and the nature of Python bytecode:

- 🔨 **Some files decompile to 100% working source code** – Clean and executable
- 🔧 **Some files produce partial code** – May have missing sections or syntax errors
- 📋 **Some files only yield `.dis` output** – Raw disassembly when decompilation fails
- ❓ **Some files are completely unrecoverable** – Corrupted, heavily obfuscated, or unsupported Python versions

Files with `.dis` extension contain Python bytecode disassembly – not source code, but still useful for understanding program flow. Think of it as assembly language for Python.

---

## 🔥 Featured Decompilations

### 📌 Educational Examples
- **Obfuscation Techniques** – Before/after comparison of obfuscated vs clean code
- **Pyc Structure** – Raw bytecode vs decompiled source side-by-side
- **Failed Decompilations** – Examples of `.dis` files and why decompilation failed

---

## 🚀 Getting Started

Want to try decompiling Python yourself? Here's how:

### Step 1: Run the tools
```bash
# Using uncompyle6
uncompyle6 file.pyc > file_decompiled.py

# Using pycdc (for newer Python versions)
pycdc file.pyc > file_decompiled.py
```

### Step 2: Stare at the screen for 3 hours
```bash
# No command for this. Just pure suffering.
```

### Step 3: When decompilation fails, get disassembly
```bash
python -m dis file.pyc > file_disassembled.dis
```

### Step 4: Stare at the screen for another 5 hours
```bash
# You're now officially a reverse engineer.
# Congratulations? 🎉
```

### Extract and decompile PyInstaller executable:
```bash
# Extract the executable
python pyinstxtractor.py your_app.exe

# Decompile the extracted .pyc files
cd your_app_extracted
uncompyle6 struct.pyc > struct.py

# Question all your life choices
echo "Why did I choose this career path?" >> existential_crisis.txt
```

---

## 📚 Learning Resources

- [Python Bytecode Decompilation Guide](https://github.com/rocky/python-uncompyle6/wiki)
- [Reverse Engineering Python Malware](https://www.youtube.com/watch?v=example)
- [PyInstaller Extraction Tutorial](https://medium.com/@example)
- [Understanding Python Obfuscation](https://github.com/example/awesome-python-obfuscation)
- [Reading Python Disassembly](https://docs.python.org/3/library/dis.html)
- [Therapy Options for Reverse Engineers](https://www.betterhelp.com) (you'll need this)

---

## 🤝 Contributing

Have an interesting Python decompilation to share? Found a better tool or technique? Contributions are welcome!

Please ensure:
- ✅ You have permission to share the decompiled code
- ✅ Include original file hash (MD5/SHA256) for reference
- ✅ Add build/decompilation notes in a separate `.txt` file
- ✅ Note whether the file is full source, partial, or `.dis` only
- ✅ Include a "how many hours of staring this took" metric (mandatory)
- ❌ No proprietary or copyrighted commercial software

---

## ⚖️ Legal & Ethical Guidelines

This repository exists for:
- 🔬 Security research and education
- 🛡️ Malware analysis and defense development
- 📖 Learning programming concepts through real examples
- 🔍 Understanding software behavior
- 😭 Developing a unhealthy relationship with your computer screen

Please use this knowledge responsibly. The maintainer ([@AtomixClub](https://github.com/AtomixClub)) is not responsible for misuse of the provided code, or the existential dread that comes with reading decompiled Python.

---

## 📊 Repository Stats

![GitHub stars](https://img.shields.io/github/stars/AtomixClub/CracksTheCodes?style=social)
![GitHub forks](https://img.shields.io/github/forks/AtomixClub/CracksTheCodes?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/AtomixClub/CracksTheCodes?style=social)
![GitHub license](https://img.shields.io/github/license/AtomixClub/CracksTheCodes)
![Hours spent staring](https://img.shields.io/badge/hours%20spent%20staring-847%20hours-blue)

---

## ⭐ Support the Project

If you find this collection useful:
- ⭐ **Star this repository** on GitHub
- 🐛 Report issues or suggest improvements
- 🔗 Share with fellow researchers and enthusiasts
- ☕ [Buy me a coffee](https://www.buymeacoffee.com/AtomixClub) (I need it after all that staring)

---

**Happy Reversing!** 🐍🔓

*— AtomixClub*

*P.S. If you're reading this and wondering why your decompiled code looks like garbage, welcome to the club. Stare harder.*
