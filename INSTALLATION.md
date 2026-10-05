# راهنمای نصب ClipBank

## دانلود رسمی

آخرین نسخه را فقط از صفحه Releases همین Repository دریافت کنید:

https://github.com/preemax/ClipBank/releases/latest

نسخه فعلی:

- **Version:** v1.1.38
- **Installer:** `ClipBank-Setup-v1.1.38.exe`
- **Platform:** Windows 10 / Windows 11
- **Architecture:** x64
- **Package:** Self-contained

## نصب تازه

1. فایل Setup را از Releases دانلود کنید.
2. فایل نصب را اجرا کنید.
3. License Agreement فارسی را مطالعه و تأیید کنید.
4. Scope نصب را انتخاب کنید:
   - فقط کاربر فعلی
   - همه کاربران
5. نوع نصب را انتخاب کنید:
   - **Typical** — تنظیمات پیشنهادی
   - **Full** — تمام مؤلفه‌های قابل نصب
   - **Custom** — انتخاب دستی گزینه‌ها
6. مسیر نصب و میانبرها را انتخاب کنید.
7. صفحه Summary را بررسی و نصب را شروع کنید.

## Upgrade نسخه قبلی

برای ارتقا، نیازی به حذف نسخه قبلی نیست.

Setup نسخه جدید را اجرا کنید. Installer نسخه نصب‌شده را شناسایی می‌کند و فایل‌های برنامه را به نسخه جدید ارتقا می‌دهد، در حالی که داده‌ها و تنظیمات کاربر حفظ می‌شوند.

## Repair / Modify / Uninstall

با اجرای مجدد Setup همان نسخه، حالت Maintenance در دسترس است:

- **Repair** — نصب مجدد فایل‌های برنامه
- **Modify** — تغییر گزینه‌های نصب
- **Uninstall** — حذف برنامه

Uninstall از Windows Settings > Apps > Installed apps نیز در دسترس است.

## پیش‌نیازها

نسخه v1.1.38 به‌صورت **Self-contained** منتشر شده است؛ بنابراین در حالت عادی نصب جداگانه .NET Runtime لازم نیست.

زیرساخت Setup برای بررسی پیش‌نیازها آماده است. اگر نسخه‌ای در آینده به Runtime یا Component خارجی نیاز داشته باشد، Setup قبل از ادامه نصب آن را بررسی خواهد کرد.

## بررسی صحت فایل

SHA-256 فایل رسمی v1.1.38:

```text
e5432694ab5b667686c5e31ee3335bd18fd31ba1a2c0ca1b0d51e0ce6806c454
```

برای بررسی در PowerShell:

```powershell
Get-FileHash .\ClipBank-Setup-v1.1.38.exe -Algorithm SHA256
```

## Windows SmartScreen

در صورتی که Windows برای یک نسخه جدید هشدار SmartScreen نمایش دهد، نام فایل، منبع دانلود و SHA-256 را با اطلاعات Release رسمی مقایسه کنید. فایل‌های ClipBank را فقط از Releases رسمی همین Repository دریافت کنید.
