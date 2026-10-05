# ClipBank

<p align="center">
  <strong>Clipboard manager for Windows — سریع، سبک و قابل تنظیم</strong>
</p>

<p align="center">
  <img alt="Release" src="https://img.shields.io/github/v/release/preemax/ClipBank">
  <img alt="Windows" src="https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?logo=windows&logoColor=white">
  <img alt="Architecture" src="https://img.shields.io/badge/Architecture-x64-lightgrey">
  <img alt="Downloads" src="https://img.shields.io/github/downloads/preemax/ClipBank/total">
</p>

---

**ClipBank** یک Clipboard Manager برای Windows است که مدیریت متن‌ها، تصاویر، مسیر فایل‌ها و چند بانک مستقل Clipboard را سریع‌تر و منظم‌تر می‌کند.

## ⬇️ دانلود

### آخرین نسخه: v1.1.38

**[دانلود ClipBank-Setup-v1.1.38.exe](https://github.com/preemax/ClipBank/releases/download/v1.1.38/ClipBank-Setup-v1.1.38.exe)**

یا صفحه کامل انتشارها را باز کنید:

**[GitHub Releases](https://github.com/preemax/ClipBank/releases/latest)**

| مشخصات فایل | مقدار |
|---|---|
| Version | v1.1.38 |
| Platform | Windows 10 / 11 |
| Architecture | x64 |
| Package | Self-contained |
| Installer | Windows Setup |
| SHA-256 | `e5432694ab5b667686c5e31ee3335bd18fd31ba1a2c0ca1b0d51e0ce6806c454` |

> نسخه فعلی Self-contained است؛ در حالت عادی نیازی به نصب جداگانه .NET Runtime ندارد.

## ✨ امکانات

| قابلیت | توضیح |
|---|---|
| Clipboard Banks | چند بانک مستقل برای نگهداری و دسترسی سریع به کپی‌ها |
| Recent Copies | نمایش آخرین کپی‌ها با تعداد قابل تنظیم از 10 تا 500 |
| Tray Popup | دسترسی سریع از System Tray و جابه‌جایی صفحه‌ای بین بانک‌ها |
| Text / Image / File | پشتیبانی از متن، تصویر و مسیر فایل |
| Hover Preview | پیش‌نمایش محدود و سریع متن و تصویر |
| Quick Paste | Paste سریع پس از انتخاب آیتم |
| Favorites | لیست‌های موردعلاقه و Pin شده |
| Most Used | دسترسی به آیتم‌های پرکاربرد |
| Global Hotkeys | میانبرهای سراسری قابل تنظیم |
| Dark / Light | تم روشن و تیره با پالت مرکزی |
| Persian UI Support | پشتیبانی مناسب از متن فارسی و تقویم جلالی |
| Image Preview | Zoom، Pan و پیش‌نمایش تصویر |
| Standard Installer | Upgrade / Repair / Modify / Uninstall |

## 🧭 Tray

با کلیک روی آیکن ClipBank در System Tray، صفحه‌های Tray با فلش‌های Header به‌صورت چرخه‌ای جابه‌جا می‌شوند:

`Bank 1 → Bank 2 → ... → Recent Copies → Edge Shortcuts → Bank 1`

در هر لحظه فقط یک صفحه نمایش داده می‌شود.

## 🛠 نصب و ارتقا

برای نصب تازه یا Upgrade نسخه قبلی، Setup جدید را اجرا کنید. Installer نسخه موجود را شناسایی می‌کند و مسیر استاندارد Upgrade را انجام می‌دهد.

راهنمای کامل: **[INSTALLATION.md](INSTALLATION.md)**

## 🧾 تغییرات نسخه‌ها

تغییرات نسخه‌های منتشرشده در **[CHANGELOG.md](CHANGELOG.md)** ثبت می‌شود.

## 🐞 گزارش خطا و پیشنهاد

- **[ثبت Bug](https://github.com/preemax/ClipBank/issues/new?template=bug_report.md)**
- **[ثبت پیشنهاد قابلیت](https://github.com/preemax/ClipBank/issues/new?template=feature_request.md)**
- راهنمای پشتیبانی: **[SUPPORT.md](SUPPORT.md)**

هنگام گزارش خطا، نسخه ClipBank، نسخه Windows، مراحل بازتولید و در صورت امکان Screenshot را اضافه کنید.

## 🔒 بررسی فایل دانلودی

برای بررسی SHA-256 فایل در PowerShell:

```powershell
Get-FileHash .\ClipBank-Setup-v1.1.38.exe -Algorithm SHA256
```

مقدار خروجی نسخه v1.1.38 باید برابر باشد با:

```text
e5432694ab5b667686c5e31ee3335bd18fd31ba1a2c0ca1b0d51e0ce6806c454
```

## ℹ️ درباره Repository

این Repository برای **انتشار نسخه‌های رسمی، مستندات، Changelog و دریافت گزارش کاربران** استفاده می‌شود. سورس برنامه در حال حاضر در این Repository منتشر نشده است.

---

<p align="center"><strong>PREEMAX / ClipBank</strong></p>
