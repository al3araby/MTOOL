# el3araby

[GitHub Repository](https://github.com/al3araby/MTOOL.git) 🚀🔥

## Overview

**el3araby** is a compact Bash menu tool that centralizes several security and utility scripts into an interactive interface. It helps you download, run, and create payloads or run scans from a single menu. Designed for learning and authorized testing in labs or on systems you own. ⚠️🛡️💻🔐

---

## Features (menu mapping) ✨🔧📋

* 1 — Run **zphisher** 📡🔍
* 2 — Run **ELARABYGBS** 🧰
* 3 — Create an **Android payload** (msfvenom) 📱💣
* 4 — Create an Android payload using an **original APK** 🛠️📦
* 5 — Create a **Python payload** (msfvenom) 🐍💣
* 6 — Run **Metasploit listener** (handler for APK/PY) 🎧🪄
* 7 — Download **zphisher** ⬇️
* 8 — Download **ELARABYGBS** ⬇️🔗
* 9 — Scan IP or domain using **nmap** 🌐🔎
* 10 — Download & install **hackingtool** 🗃️🛠️
* 11 — Run **hackingtool** ▶️
* 12 — Run **sqlmap** against a target (discovery: `--dbs`) 🗄️🔓
* 13 — Create a **QR code** from a link (uses `qrencode`) 🔳➡️🔗
* 14 — Download **instainsane** 📥📸
* 15 — Run **instainsane** ▶️📸
* 16 — Install **apktool 2.9.3**, `apksigner`, and `zipalign` 🛠️📦
* 17 — Install required fonts/tools for banner (figlet, lolcat) 🔤🌈
* 18 — Add a figlet banner name to your shell config (e.g. `~/.zshrc`) ✍️✨
* 19 — Run included **temp mail** tool (Python script) 📮⏳
* 20 — Help / open author Instagram ❓📸
* 21 — Update & upgrade the system ⬆️🔁
* 22 — Contact / author info 🙋‍♂️📬

---

## Requirements ✅

* Linux (Debian/Ubuntu recommended)
* Bash
* `git`, `wget`, `python3`, `sudo`
* `msfvenom` / `msfconsole` (Metasploit) for payloads & listener
* `nmap`, `sqlmap` where relevant
* `qrencode` for QR generation (the script installs it if needed)

> Some options attempt to install dependencies automatically, but pre-installing core tools and running as a `sudo`-capable user is recommended. ⚙️🔒

---

## Installation 🧩

```bash
git clone https://github.com/al3araby/MTOOL.git
cd MTOOL
chmod +x tool.sh
./tool.sh
```

You can also source the script and call the `el3araby` function directly from your shell.

---

## Safety & Best Practices 🛡️📚

* **Only** run attacks against systems you own or have explicit written permission to test. ⚖️🚫
* Use isolated environments (VMs, local labs) for experiments. 🧪🖥️
* Inspect third-party scripts before running them. 🔍📜
* Keep tools updated and follow vendor guidance. 🔄✅

---

## Contributing 🤝

Contributions are welcome. Maintain clear safety notes and provide tests or usage examples for new additions. All pull requests that add offensive capabilities must include explicit safety warnings and responsible-use documentation.

---

## License 📜

Add a license file if you want to define reuse terms (MIT recommended for permissive reuse). 📝

---

## Author / Contact 🙋‍♂️

* GitHub: `https://github.com/al3araby/MTOOL.git` 🔗
* Instagram: `https://instagram.com/el3rraby` 📸
* Telegram: `@MM_EZ` 💬

---

*README updated: full English text, more emojis, and the requested phrase removed.*
