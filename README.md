<h4 align="center"> If you find this GitHub repo useful, please consider giving it a star! ⭐️ </h4> 
<p align="center">
    <a href="https://spyboy.in/twitter">
      <img src="https://img.shields.io/badge/-TWITTER-black?logo=twitter&style=for-the-badge">
    </a>
    &nbsp;
    <a href="https://spyboy.in/">
      <img src="https://img.shields.io/badge/-spyboy.in-black?logo=google&style=for-the-badge">
    </a>
    &nbsp;
    <a href="https://spyboy.blog/">
      <img src="https://img.shields.io/badge/-spyboy.blog-black?logo=wordpress&style=for-the-badge">
    </a>
    &nbsp;
    <a href="https://spyboy.in/Discord">
      <img src="https://img.shields.io/badge/-Discord-black?logo=discord&style=for-the-badge">
    </a>
  
</p>

<p align="center">
  <img width="20%" src="https://github.com/spyboy-productions/CamXploit/blob/main/CCTV recon.jpg" />
</p>



CamXploit is a reconnaissance tool designed to help researchers and security enthusiasts check if an IP address is hosting an exposed CCTV camera. It scans common camera ports, checks for login pages, tests default credentials, and provides useful search links for further investigation.  

⚠️ **Disclaimer:** This tool is intended for educational and security research purposes **only**. Unauthorized scanning of systems you do not own is illegal. Use responsibly.  

---

## 🚀 **Features**  
✔️ **Scans common CCTV ports** (80, 443, 554, 8080, 8443)  
✔️ **Detects exposed camera login pages**  
✔️ **Checks if the device is a camera stream**  
✔️ **Identifies camera brands & known vulnerabilities**  
✔️ **Tests for default credentials on login pages**  
✔️ **Provides manual search links (Shodan, Censys, Zoomeye, Google Dorking)**  
✔️ **Google Dorking suggestions for deeper recon**  

---

## 🛠️ **Installation**  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/yourusername/CamXploit.git
```
```
cd CamXploit
```  
```bash
pip install -r requirements.txt
```
---
```
python CamXploit.py
```
Enter the **public IP address** of the target device when prompted.  

### **🔍 What It Does:**  
1️⃣ **Scans open ports** (Common CCTV ports)  
2️⃣ **Checks if a camera is present**  
3️⃣ If a camera is found, it:  
   - Searches for **login pages**  
   - Checks **default credentials**  
   - Identifies **camera brand & vulnerabilities**  
4️⃣ Provides **manual search URLs** for deeper investigation  

---

## 📸 **Example Output**  

<img width="100%" align="centre" src="https://github.com/spyboy-productions/CamXploit/blob/main/demo.png" />

---

## 🤖 **To-Do & Future Features**  
- [ ] Add multi-threaded scanning for speed  
- [ ] Expand camera brand detection  
- [ ] Implement logging feature  

---
## 🙌 **Contributions**  
Feel free to submit issues, suggestions, or pull requests!  

<h4 align="center"> If you find this GitHub repo useful, please consider giving it a star! ⭐️ </h4> 
