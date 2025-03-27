

# 📌 CMD Weather Fetcher 🌦️  

<br>

[![License](https://img.shields.io/github/license/nishuR27/cmdWeatherFetch?style=social)](LICENSE)  
[![Stars](https://img.shields.io/github/stars/nishuR27/cmdWeatherFetch?style=social)](https://github.com/nishuR27/cmdWeatherFetch)  
![Profile Views](https://komarev.com/ghpvc/?username=nishuR27&color=blueviolet&style=social)  
[![Follow Me](https://img.shields.io/badge/-Follow%20Me-blueviolet?style=social)](https://github.com/nishuR27)  

<br>

A **lightweight and powerful CLI tool** to fetch real-time weather updates **directly in the terminal** using simple commands! 🌍  

<br>

---

## 🚀 Features  
- ✅ Get **real-time weather updates** for any city.  
- ✅ Supports **temperature, humidity, wind speed, and conditions**.  
- ✅ Works on **Windows, macOS, and Linux**.  
- ✅ No API key required – **completely free to use**.  
- ✅ Extremely fast & lightweight.  
- ✅ Uses `curl`, which is available by default on most systems.  
<br>

---

## 📥 Installation  

### 🔧 **Prerequisites**  
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

### 🔹 Get Weather for a City  
```bash
curl wttr.in/NewYork
```  
<br>

### 🔹 Get Weather for Your Current Location  
```bash
curl wttr.in
```  
<br>

### 🔹 Get Weather in Celsius  
```bash
curl wttr.in/London?format=%C+%t
```  
<br>

### 🔹 Get a Compact Weather Report  
```bash
curl wttr.in/Tokyo?format=3
```  
<br>

### 🔹 Display Weather in Windows Command Prompt (cmd)  
Windows users may need to enable UTF-8 support in the terminal:  
```powershell
chcp 65001   # Set code page to UTF-8  
curl wttr.in/LosAngeles  
```
<br>

### 🔹 Automate Weather Updates in a Script  
You can use the tool inside scripts for automation:  
```bash
#!/bin/bash
CITY="NewYork"
curl wttr.in/$CITY
```  

---

<br>

## 🔧 Example Output  
```
Weather for New York: ☁️ 18°C  
Humidity: 73%  
Wind: 10 km/h SW  
```  
_(Your actual weather report will be displayed in the terminal)_

---

<br>

## 📝 License  
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.  

---

<br>

### 🌟 Show Some Love  
If you like this tool, drop a ⭐ on [GitHub](https://github.com/nishuR27/cmdWeatherFetch)! 🚀  

<br>

### Fun time  
![Jokes Card](https://readme-jokes.vercel.app/api?username=nishuR27&theme=algolia&hideBorder)  
![Quotes](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=algolia)  

<br>

### <h2>Get in Touch</h2>  
I’m always excited to connect with fellow developers, share insights, and learn from the experiences of others. Whether you have questions, want to discuss a project, or just want to chat about tech, feel free to reach out!  
<br>  
You can email me at [nishangithub.com@gmail.com](mailto:nishangithub.com@gmail.com).  
