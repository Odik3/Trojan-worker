<h1 align="center">
  ورکر تروجان
</h1>

<h2 align="center">
دسترسی به کانفیگ‌های تروجان از طریق سی‌دی‌ان کلاودفلیر.
  <h3>
    <a href="README.md">English 🇬🇧</a> | 🇮🇷 فارسی
  </h3> 
</h2>

[![نسخه](https://img.shields.io/github/v/release/surfboardv2ray/Trojan-worker?label=Version&color=blue)](https://github.com/surfboardv2ray/Trojan-worker/releases/latest)
[![دانلود](https://img.shields.io/github/downloads/surfboardv2ray/Trojan-worker/total?label=Downloads)](https://github.com/surfboardv2ray/Trojan-worker/releases/latest)
[![استار](https://img.shields.io/github/stars/surfboardv2ray/Trojan-worker?style=flat&label=Stars&color=tomato
)](https://github.com/surfboardv2ray/Trojan-worker)

## مقدمه
🟢 در این اسکریپت علاوه بر کانفیگ‌های vmess و vless، کانفیگ‌های Trojan رو هم پشت CDN کلاودفلیر قرار میدیم.

## نصب
1. در سایت کلاودفلیر https://dash.cloudflare.com ثبت نام و ایمیل خود را تایید کنید.
2. به بخش `Workers and Pages` رفته و یه ورکر جدید بسازید.
3. روی `Edit Code` کلیک کنید تا وارد محیط ویرایش جاوا اسکریپت شوید.
4. آخرین نسخه [ورکر تروجان](https://github.com/Surfboardv2ray/Trojan-worker/releases/latest/download/worker.js) رو دانلود کنید. سپس فایل رو باز کنید و همه محتوا رو کپی کنید.
5. محتوایی که کپی کردید رو در محیط ادیت (مرحله 3) paste کنید.
6. روی `Deploy` بزنید (اگر این دکمه روشن نمیشود، یکبار کلید ترکیبی Ctrl+S را امتحان کنید)
7. آدرس سابسکریپشن شما به این صورت خواهد بود. `https://{your_worker_address}.workers.dev/sub/{your_clean_ip}`

## ویرایش لینک‌های منبع
🟡 لینک‌های سابسکریپشن منبع خود را در بخش `subLinks` ابتدای اسکریپت میتونید اضافه کنید. هر دو فرمت استاندارد و base64 پشتیبانی میشوند.

🟡 دقت کنید که از بین کانفیگ‌های لینک‌های سابسکریپشن، فقط کانفیگ‌های Vless و Vmess و Trojan با شبکه WS، امنیت TLS و پورت 443 برداشت خواهند شد.

## سایر نکات
🟡 برای پیدا کردن آیپی تمیز از [اسکنرها](https://ircf.space/scanner.html) استفاده کنید.

![0](./assets/redline.gif)
