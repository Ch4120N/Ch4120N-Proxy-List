

<div align="center">

# 🌐 Ultimate Free Proxy List 🚀

![Total Alive Proxies](https://img.shields.io/badge/Total%20Alive-5456-brightgreen?style=for-the-badge)
![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--07--12-blue?style=for-the-badge)
![Update Frequency](https://img.shields.io/badge/Updates-Every%20Hour-orange?style=for-the-badge)
![Maintainer](https://img.shields.io/badge/Maintained%20By-Ch4120N-purple?style=for-the-badge)

</div>

<br>

## 📖 About
Welcome to the most comprehensive, automatically updated, and strictly validated free proxy list on GitHub! 
This repository is actively **Maintained by Ch4120N** and leverages advanced multi-threading to ensure you always have access to the freshest, fastest, and most reliable proxies.

## ✨ Key Features
- 🔄 **Auto-Updated:** Refreshes every Hour via GitHub Actions.
- 🛡️ **Strictly Validated:** Every single proxy is checked line-by-line for real availability.
- 🌍 **Country Sorted:** Proxies are neatly categorized by country using dedicated regional sources.
- 🚀 **High Performance:** Multi-threaded fetching and validation for maximum speed.
- 📡 **Multi-Protocol:** Supports HTTP, HTTPS, SOCKS4, SOCKS5, and Telegram MTProto.
- 🧹 **Clean & Deduplicated:** Advanced algorithms remove dead and duplicate entries.

## 📊 Live Proxy Statistics

| 📡 Protocol | 🔢 Alive Count | 🔗 Direct Download |
| :--- | :---: | :--- |
| **HTTP/HTTPS** | `515` | [📥 Download `http.txt`](proxies/http.txt) |
| **SOCKS4** | `618` | [📥 Download `socks4.txt`](proxies/socks4.txt) |
| **SOCKS5** | `4,077` | [📥 Download `socks5.txt`](proxies/socks5.txt) |
| **MTProto** | `246` | [📥 Download `mtproto.txt`](proxies/mtproto.txt) |
| **🔥 ALL** | **`5,456`** | [📥 Download `all.txt`](proxies/all.txt) |

> 💡 **Pro Tip:** The `all.txt` files include the protocol scheme (e.g., `socks5://`, `http://`) so you know exactly what protocol each proxy uses!

## 🌍 Country-Specific Proxies 🗺️
Need a proxy from a specific region? We've got you covered! 
Proxies are automatically fetched and sorted into country directories from dedicated regional sources.

👉 **[Browse All Countries Here](countries/)**

*Structure: `countries/{COUNTRY_CODE}/proxies.txt` (e.g., `countries/US/proxies.txt`)*

## 🛠️ How to Use

### 🐍 Python (Requests)
```python
import requests

proxies = {
    "http": "http://192.168.1.1:8080",
    "https": "http://192.168.1.1:8080",
}
response = requests.get("https://httpbin.org/ip", proxies=proxies)
print(response.json())
```

### 💻 cURL (Terminal)
```bash
curl -x http://192.168.1.1:8080 https://httpbin.org/ip
curl -x socks5://192.168.1.1:1080 https://httpbin.org/ip
```

## ⚠️ Disclaimer
This project is for **educational and research purposes only**. 
The maintainer is not responsible for any misuse of these proxies. Always ensure you have permission to route traffic through any proxy server. Use responsibly!

---

<div align="center">
  <b>🛠️ Actively Maintained by <a href="https://github.com/Ch4120N">Ch4120N</a> 🛠️</b>
  <br>
  <i>If you find this useful, consider dropping a ⭐ on the repository!</i>
</div>
