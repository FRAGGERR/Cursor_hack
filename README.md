<div align="center">

# 🚀 Cursor Helper Commands  

<img width="1199" height="307" alt="Image" src="https://github.com/user-attachments/assets/d75c8948-7f45-4b71-8909-ae073beb8579" />

![GitHub last commit](https://img.shields.io/github/last-commit/yuaotian/go-cursor-help?style=for-the-badge&logo=github) ![GitHub repo size](https://img.shields.io/github/repo-size/yeongpin/cursor-free-vip?style=for-the-badge&color=blueviolet) ![Platform](https://img.shields.io/badge/Platform-macOS-lightgrey?style=for-the-badge&logo=apple) ![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

A curated set of handy commands to fix common issues and enhance your **Cursor** experience.  
Each command is provided with its source and usage. Use them responsibly.  

</div>

---

## 📌 1. Modify Cursor Mac ID  
**Origin:** [yuaotian/go-cursor-help](https://github.com/yuaotian/go-cursor-help)  

```bash
curl -fsSL https://aizaozao.com/accelerate.php/https://raw.githubusercontent.com/yuaotian/go-cursor-help/refs/heads/master/scripts/run/cursor_mac_id_modifier.sh -o ./cursor_mac_id_modifier.sh && sudo bash ./cursor_mac_id_modifier.sh && rm ./cursor_mac_id_modifier.sh


```
## 📌 2. Install Cursor Free VIP  

**Origin:** [cursor-free-vip](https://github.com/yeongpin/cursor-free-vip)  

```bash
curl -fsSL https://raw.githubusercontent.com/yeongpin/cursor-free-vip/main/scripts/install.sh -o install.sh && chmod +x install.sh && ./install.sh
```

✔️ Installs the Cursor Free VIP package.
🔧 Makes setup painless with a single script.


## 📌 3. Fix Permission Issues  

**Origin:** Local workaround  

```bash
sudo chown -R $(whoami) "/Users/hardikchhipa/Library/Application Support/Cursor"
```

Notes:
- Replace the username in the path if this is being used on another Mac.
- Close Cursor before running this, then reopen it.

---

## 🛠️ Troubleshooting
- If a script fails with a network error, try again on a stable connection or use a different network.
- For `permission denied`, prepend `sudo` where appropriate or ensure the script is executable (`chmod +x <file>`).
- After system-level changes, a reboot can resolve lingering issues.

---

## ⚠️ Disclaimer
These commands are provided as-is. Review and understand each script before executing, especially those requiring `sudo`. Proceed at your own risk.
