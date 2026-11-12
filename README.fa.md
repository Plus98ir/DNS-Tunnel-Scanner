# DNS Tunnel Scanner

<a href="https://hits.sh/github.com/Plus98ir/DNS-Tunnel-Scanner/"><img src="https://hits.sh/github.com/Plus98ir/DNS-Tunnel-Scanner.svg?style=for-the-badge&label=views&color=2dd4bf" alt="Views"></a> <a href="https://corenetbase.com/#support"><img src="https://img.shields.io/badge/support-buy%20me%20a%20coffee-e11d2a?style=for-the-badge&logo=buymeacoffee&logoColor=white" alt="Support"></a>
<a href="https://github.com/Plus98ir/DNS-Tunnel-Scanner/releases/latest"><img src="https://img.shields.io/github/release-date/Plus98ir/DNS-Tunnel-Scanner?style=for-the-badge&label=latest%20build&color=0e7490" alt="Latest build"></a>

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
<table><tr><td><a href="https://github.com/Plus98ir/DNS-Tunnel-Scanner/blob/main/README.md">🇺🇸 English</a></td><td><b>🇮🇷 فارسی</b></td></tr></table>
</div>

وب‌سایت: https://corenetbase.com/DNS-Tunnel-Scanner/

![DNS Tunnel Scanner](DNS-Tunnel-Scanner.png)

### Download · دانلود

| | Download | |
|---|---|---|
| **Android** | [DNS-Tunnel-Scanner.apk](https://github.com/Plus98ir/DNS-Tunnel-Scanner/releases/latest/download/DNS-Tunnel-Scanner.apk) | Android 7+ |
| **Windows** | [DNS-Tunnel-Scanner.exe](https://github.com/Plus98ir/DNS-Tunnel-Scanner/releases/latest/download/DNS-Tunnel-Scanner.exe) | double-click; no Python needed |

---

<div dir="rtl">

در قطعی اینترنت معمولاً فقط DNS کار می‌کند. تونل DNS ترافیک شما را داخل پرس‌وجوهای DNS، از طریق یک **ریزالور DNS**، به سرور تونل می‌برد. این‌که کدام ریزالورها آن را رد می‌کنند برای هر اپراتور فرق دارد و عوض می‌شود.

DNS Tunnel Scanner ریزالورها را روی همان اینترنتی که هستید تست می‌کند و فقط آن‌هایی را نگه می‌دارد که **واقعاً** کار می‌کنند:

۱. **فیلتر سریع**: یک نام تصادفی زیر دامنه‌ی تونل شما. فقط سرور تونل شما می‌تواند جوابش را بدهد؛ پس جواب یعنی ریزالور به سرور می‌رسد (هزاران ریزالور در دقیقه).

۲. **تست واقعی**: خود کلاینت StormDNS فقط با همان یک ریزالور اجرا می‌شود، اتصال تونل می‌سازد، یک صفحه‌ی HTTPS از داخلش باز می‌کند و سرعت را می‌سنجد. اگر اتصال نشد، یک بار دیگر امتحان می‌شود.

۳. **اشتراک**: ریزالورهای سالم، سریع‌ترین اول، به‌صورت متن، فایل یا QR، همراه لینک پروفایل WhiteDNS.

**استفاده**

۱. APK را نصب کنید (اندروید ۷ به بالا) یا EXE را اجرا کنید (ویندوز ۱۰/۱۱، پایتون لازم نیست).

۲. لینک پروفایل را یک بار بچسبانید (`stormdns://…` یا `masterdns://…`، مثلاً از WhiteDNS ← خروجی پروفایل). روی دستگاه خودتان می‌ماند؛ به پنل نیازی نیست.

۳. منبع‌ها را تیک‌خورده نگه دارید (DNS خود دستگاه، ریزالورهایی که قبلاً همین‌جا کار کرده‌اند، ریزالورهای عمومی ایرانی و خارجی)، اگر خواستید IP یا رنج CIDR خودتان را اضافه کنید و **شروع اسکن** را بزنید. چیزی کار نکرد؟ **اسکن عمیق** را روشن کنید: رنج آدرس‌های اپراتورتان را برای ریزالورهای بازی که در هیچ لیستی نیستند می‌گردد.

۴. در WhiteDNS: لینک پروفایل را وارد کنید و لیست ریزالورها را بچسبانید.

نتیجه به اپراتور بستگی دارد: روی هر سیم‌کارت / وای‌فای جدا اسکن کنید. برنامه ریزالورهای سالم را برای هر شبکه جدا یادش می‌ماند و دفعه‌ی بعد اول همان‌ها را تست می‌کند.

</div>

---

<div dir="rtl">

موتور تونل: [StormDNS](https://github.com/nullroute1970/StormDNS) (MIT)، از سورس ساخته شده.

</div>
