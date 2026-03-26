<p align="center">
  <img src="https://via.placeholder.com/80x80?text=DN" width="80" style="border-radius:50%">
</p>

<h1 align="center">🔒 DarkNova Code Obfuscator</h1>

<p align="center">
  <strong>Browser‑powered JavaScript & HTML obfuscator – unlimited, free, and fully local.</strong><br>
  <a href="https://mrdarknova.github.io/DarkNova-Obfuscator">🌐 Live Demo</a> •
  <a href="#-features">✨ Features</a> •
  <a href="#-obfuscation-levels">⚙️ Levels</a> •
  <a href="#-how-to-use">🚀 How to Use</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0.0-blue?style=flat-square">
  <img src="https://img.shields.io/github/deployments/MrDarkNova/DarkNova-Obfuscator/github-pages?label=GitHub%20Pages&style=flat-square&color=2ea44f">
  <img src="https://img.shields.io/github/license/MrDarkNova/DarkNova-Obfuscator?style=flat-square&color=red">
  <img src="https://img.shields.io/github/last-commit/MrDarkNova/DarkNova-Obfuscator?style=flat-square">
</p>

---

## ✨ Features

<div align="center">
  <table>
     <tr align="center">
       <td>🌐 <b>100% Client‑Side</b><br>No server, no uploads – your code stays local</td>
       <td>⚡ <b>Unlimited Size</b><br>Obfuscate files of any size</td>
       <td>🔒 <b>5 Protection Levels</b><br>From Default to Extreme</td>
     </tr>
     <tr align="center">
       <td>📄 <b>HTML Support</b><br>Obfuscate `<script>` blocks inside HTML</td>
       <td>📁 <b>File Upload</b><br>Drag & drop or upload .js / .html</td>
       <td>💾 <b>Save & Copy</b><br>One‑click download or clipboard copy</td>
     </tr>
     <tr align="center">
       <td>🎨 <b>Dark/Light Theme</b><br>Persistent preference</td>
       <td>📋 <b>Line Numbers</b><br>Sync scrolling and line count</td>
       <td>🚀 <b>Keyboard Shortcut</b><br>`Ctrl+Enter` to obfuscate</td>
     </tr>
   </table>
</div>

---

## ⚙️ Obfuscation Levels

| Level | Description | Protection |
|-------|-------------|------------|
| **Default** | Standard obfuscation with string array & compaction | ★☆☆☆☆ |
| **Low** | Basic transformation, good for readability | ★★☆☆☆ |
| **Medium** | Control flow flattening + dead code injection | ★★★☆☆ |
| **High** | Debug protection, self‑defending, string encoding | ★★★★☆ |
| **Extreme** | All features maxed – RC4 strings, numbers to expressions, full self‑defense | ★★★★★ |

---

## 🚀 How to Use

### 🔗 Online (GitHub Pages)
1. Visit [https://mrdarknova.github.io/DarkNova-Obfuscator](https://mrdarknova.github.io/DarkNova-Obfuscator)
2. Paste your JavaScript or HTML code, or upload a file.
3. Choose a protection level.
4. Click **OBFUSCATE** (or press `Ctrl+Enter`).
5. Copy the output or download it as a file.

### 💻 Local (offline)
```bash
git clone https://github.com/MrDarkNova/DarkNova-Obfuscator.git
cd DarkNova-Obfuscator
python3 -m http.server 8000
