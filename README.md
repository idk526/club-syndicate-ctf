# Club Syndicate CTF 2026 🚩

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Security](https://img.shields.io/badge/Security-CTF-neon?style=for-the-badge&color=00e5ff)

This repository contains the front-end source code and custom challenges for the **Club Syndicate Capture The Flag (CTF)** event, developed for the computer science club at Manipal University Jaipur. 

### 🎯 Project Overview
When designing this event, my goal was to build a fast, lightweight static platform to host local security challenges without the overhead of a complex backend server. I engineered the challenges from scratch to give members practical, hands-on experience with real-world vulnerabilities. 

I built and tested the challenge environments primarily on Kali Linux, tailoring them to be solved using industry-standard command-line tools.

### 🧩 Challenge Architecture
The platform currently hosts 6 challenges scaling from beginner to intermediate difficulty:

* **Forensics & Steganography:** Hidden payloads in images, audio frequency analysis, and video structure manipulation. Structured for tools like `Exiftool`, `Steghide`, `Zsteg`, and `Binwalk`.
* **File Recovery (Magic Bytes):** A specialized challenge where players analyze a corrupted `.dat` file signature in a hex editor, repair the broken header, and decrypt it to extract the flag.
* **Web Exploitation & Cryptography:** A dedicated staging environment challenge built to teach client-side source code analysis, MD5 hashing, XOR decryption, and flawed authentication token bypass.

### 💻 Tech Stack
The platform's UI is written in pure HTML5 and CSS3 to ensure it remains lightweight. I implemented a responsive, neon-themed dark mode to replicate a classic terminal aesthetic. The site is fully static and deployed via Vercel for reliable hosting.

### 🚀 Running Locally
Because it relies entirely on static files, there are no packages or dependencies to install. You can simply clone the repository, open `index.html` directly in your browser, and start solving.
