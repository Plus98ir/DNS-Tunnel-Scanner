<h1 align="center">DNS Tunnel Scanner</h1>

<p align="center"><a href="https://hits.sh/github.com/Plus98ir/DNS-Tunnel-Scanner/"><img src="https://hits.sh/github.com/Plus98ir/DNS-Tunnel-Scanner.svg?style=for-the-badge&label=views&color=2dd4bf" alt="Views"></a> <a href="https://corenetbase.com/#support"><img src="https://img.shields.io/badge/support-buy%20me%20a%20coffee-e11d2a?style=for-the-badge&logo=buymeacoffee&logoColor=white" alt="Support"></a> <a href="https://github.com/Plus98ir/DNS-Tunnel-Scanner/releases/latest"><img src="https://img.shields.io/github/release-date/Plus98ir/DNS-Tunnel-Scanner?style=for-the-badge&label=latest%20build&color=0e7490" alt="Latest build"></a></p>

<details>
<summary><b>☕ Support · حمایت</b> — USDT (TRC20) / TRX</summary>
<br>
<p align="center"><img src="https://raw.githubusercontent.com/Plus98ir/.github/main/tron-qr.png" width="200" alt="TRON address QR"></p>

```
TA53aFyGNfSAcrCaJi9QmA9x5W47nPJcf7
```

> [!WARNING]
> **TRON network only.** Sending from ERC20 / BEP20 will lose the funds.<br>
> **فقط شبکه‌ی TRON.** ارسال از ERC20 یا BEP20 پول را از بین می‌برد.

</details>

<div align="center">

[<img src="https://flagcdn.com/w40/us.png" width="20" alt=""> &nbsp;**English**](README.md) &nbsp;&nbsp;|&nbsp;&nbsp; [<img src="https://flagcdn.com/w40/ir.png" width="20" alt=""> &nbsp;**فارسی**](README.fa.md)

</div>

Website: https://corenetbase.com/DNS-Tunnel-Scanner/

![DNS Tunnel Scanner](DNS-Tunnel-Scanner.png)

### Download · دانلود

| | Download | |
|---|---|---|
| **Android** | [DNS-Tunnel-Scanner.apk](https://github.com/Plus98ir/DNS-Tunnel-Scanner/releases/latest/download/DNS-Tunnel-Scanner.apk) | Android 7+ |
| **Windows** | [DNS-Tunnel-Scanner.exe](https://github.com/Plus98ir/DNS-Tunnel-Scanner/releases/latest/download/DNS-Tunnel-Scanner.exe) | double-click; no Python needed |

---

During an internet shutdown often only DNS still works. A DNS tunnel carries your traffic inside DNS queries, through a **DNS resolver**, to your tunnel server. Which resolvers carry it differs per ISP and changes over time.

DNS Tunnel Scanner tests them on your current network and keeps only the ones that **really** work:

1. **Quick filter**: a random name under your tunnel domain. Only your tunnel server can answer it, so an answer proves the resolver reaches the server (thousands of resolvers a minute).
2. **Real test**: the real StormDNS client starts with just that one resolver, builds a tunnel session and loads an HTTPS page through it, then measures the speed. A failed session gets a second try.
3. **Share**: the working resolvers, fastest first, as text, a file or a QR code, together with the WhiteDNS profile link.

**Use it**

1. Install the APK (Android 7+) or run the EXE (Windows 10/11, no Python needed).
2. Paste your profile link once (`stormdns://…` or `masterdns://…`, e.g. WhiteDNS → export profile). It stays on your device; no panel access is needed.
3. Keep the sources ticked (this device's DNS, resolvers that worked here before, Iranian and global public resolvers), add your own IPs or CIDR ranges if you like, and press **Start scan**. Nothing works? Turn on **Deep scan**: it searches your ISP's ranges for open resolvers no list has.
4. In WhiteDNS: import the profile link and paste the resolver list.

Results depend on the ISP: scan again on each SIM / Wi-Fi. The app remembers the working resolvers per network and tests them first next time.

---

Tunnel engine: [StormDNS](https://github.com/nullroute1970/StormDNS) (MIT), built from source.
