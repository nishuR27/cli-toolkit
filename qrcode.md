# 📌 CMD QR Code Tool

<br>

[![License](https://img.shields.io/github/license/nishuR27/cli-toolkit)](LICENSE)
[![Stars](https://img.shields.io/github/stars/nishuR27/cli-toolkit)](https://github.com/nishuR27/cli-toolkit)
![Profile Views](https://komarev.com/ghpvc/?username=nishuR27&color=blueviolet)
[![Follow Me](https://img.shields.io/badge/-Follow%20Me-blueviolet)](https://github.com/nishuR27)

<br>

A **lightweight and robust CLI tool** to generate and display QR codes **directly in the terminal** using simple commands! 🎯
<br>

---

## 🚀 Features
- ✅ Generates QR codes from any URL or text directly in CMD/Terminal.
- ✅ No need for additional UI, displays clean black-and-white QR code.
- ✅ Works on Windows, macOS, and Linux.
- ✅ Lightweight & Fast.
- ✅ Fully open-source and easy to use.
- ✅ Can be integrated into scripts and automation workflows.
- ✅ Uses `curl`, which is available by default on most systems.
<br>

---

## 📥 Installation

### 🔧 Prerequisites
Ensure you have `curl` installed (most systems have it by default). If not, install it:

```bash
# Linux (Debian/Ubuntu)
sudo apt install curl -y

# macOS (Homebrew)
brew install curl

# Windows (Chocolatey)
choco install curl
```
<br>
For Windows users who do not use Chocolatey, you can manually install `curl` from the official [CurL website](https://curl.se/download.html).

<br>

## 📌 Usage
<br>

### 🔹 Generate QR Code in CMD
```bash
curl qrenco.de/[any text or link]
```
<br>

### 🔹 Use Custom Text Instead of URL
```bash
curl qrenco.de/HelloWorld
```
<br>

### 🔹 Save QR Code Output to a File
```bash
curl qrenco.de/https://example.com > fileName.txt
```
<br>

### 🔹 Display QR Code in Windows Command Prompt (cmd)
Windows users may need to enable UTF-8 support in the terminal:
```powershell
chcp 65001   # Set code page to UTF-8
curl qrenco.de/https://example.com
```
<br>

### 🔹 Automate QR Code Generation in a Script
You can use the tool inside scripts for automation:
```bash
#!/bin/bash
URL="https://example.com"
curl qrenco.de/$URL
```

---

<br>


## 🔧 Example Output
```
█████████████████████████████████
█████████████████████████████████
████ ▄▄▄▄▄ █ ██▀▀█▄▄ █ ▄▄▄▄▄ ████
████ █   █ █  ▀█ ▀ ▀ █ █   █ ████
████ █▄▄▄█ █▀  █▄▀▄▄▄█ █▄▄▄█ ████
████▄▄▄▄▄▄▄█▄█ ▀▄█ █▄█▄▄▄▄▄▄▄████
████▄ ██  ▄█▀█▄█▄▄  █▀█▄▀ ▄ ▄████
████▀▄█▄▄ ▄▀  ▄█▀▄█ █ ▄ █▄ ▀█████
████▀▀█▀▄▀▄██▀▀▄▀▄ ▀▀▄▄▄▀▄▄ ▄████
███████▀▄▄▄ ▀ ▀ ▄ ▄ ▄▄█  ▄ ▀█████
████▄▄▄▄▄█▄▄ ▄ █▄ ▀▄ ▄▄▄ ▄▄██████
████ ▄▄▄▄▄ █▀█ █▀█▀█ █▄█ ▀▀▀█████
████ █   █ █▄▄ ▄▀▄▄█▄   ▄▄   ████
████ █▄▄▄█ █▀█▄ ▄ ▄▄▄▄ ▀▀ ▀ █████
████▄▄▄▄▄▄▄█▄███▄▄█▄█▄▄███▄▄▄████
█████████████████████████████████
█████████████████████████████████

```
_(Your actual QR code will be displayed in terminal)_

---

<br>


## 📝 License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

<br>

### 🌟 Show Some Love
If you like this tool, drop a ⭐ on [GitHub](https://github.com/nishuR27/cli-toolkit)! 🚀

<br>

### Fun time

![Jokes Card](https://readme-jokes.vercel.app/api?username=nishuR27&theme=algolia&hideBorder)
![Qoutes](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=algolia)

<br>

### <h2>Get in Touch</h2>

I’m always excited to connect with fellow developers, share insights, and learn from the experiences of others. Whether you have questions, want to discuss a project, or just want to chat about tech, feel free to reach out!
<br>
You can email me at [nishangithub.comgmail.com](mailto:nishangithub.com@gmail.com).  I’m looking forward to engaging with the developer community and exchanging ideas with fellow developers and learn from their experiences.

