<meta name="google-site-verification" content="tOP_Xt49kmM6PbEaEkpnwRIb9jQ1bvMHb_bThp8Fv2I" />

<p align="center">
  <img src="AirSat.jpg" width="500">
</p>

<p align="center">
  <span style="font-size: 26px; font-weight: bold;">🛰 AirSat Documentation</span>
</p>

<div align="center">
  <a href="#english" style="font-size: 18px; margin: 0 10px;">🇬🇧 English</a> |
  <a href="#persian" style="font-size: 18px; margin: 0 10px;">🇮🇷 فارسی</a>
</div>

---

## <span id="english">🇬🇧 English Version</span>

## 📘 Overview
**🛰 AirSat** is a satellite-based air pollution monitoring system developed for Iran using  
**Sentinel-5P (TROPOMI) Level-3 OFFL** products.  
The system provides interactive visualization, temporal aggregation, and direct data download  
for major atmospheric pollutants from **2018 to present**.

🌍 **Live website:** https://attarbashian.github.io/AirSat/  
📦 **GitHub repository:** https://github.com/Attarbashian/AirSat  

---

## 🧪 Pollutants Covered
AirSat currently supports the following Sentinel-5P products:

- 🟤 Nitrogen Dioxide (**NO₂**)
- 🟡 Sulfur Dioxide (**SO₂**)
- ⚫ Carbon Monoxide (**CO**)
- 🔵 Ozone (**O₃**)
- 🧬 Formaldehyde (**HCHO**)
- 🔥 Methane (**CH₄**)
- 🌫 UV Aerosol Index (**UVAI**)

---

## ✨ Key Features
- ⏱ Dynamic temporal averaging:
  - 7-day mean
  - 30-day mean
  - Last 3 months
  - Annual mean
  - Custom date range
- 🗺 Nationwide and provincial-scale analysis
- 🔍 Hotspot detection and comparison charts
- 📥 Direct download of:
  - GeoTIFF (scientific data)
  - PNG (visualized maps)
- 🌐 Fully bilingual interface (English / Persian)

---

## 🛰 Data Source
- 🛰 Satellite: Sentinel-5P (TROPOMI)
- 📦 Product level: Level-3
- ⚙ Processing mode: OFFL
- ☁ Platform: Google Earth Engine
- 📆 Temporal coverage: 2018–present

---

## ⚠ Important Notes
- 📐 Most pollutants are provided as **vertical column densities (mol/m²)**.
- 🚫 AirSat does **not** convert satellite products to surface concentration units.
- 🔬 CH₄ is shown as dry-air mole fraction (ppb), according to the official product definition.
- ☁ Data gaps may occur due to cloud cover, QA masking, or orbit geometry.

---

## 🎯 Intended Use
AirSat is designed for:
- 📊 Scientific visualization
- 📈 Trend analysis
- 🌍 Large-scale spatial comparison

> ⚖ AirSat is intended for research, visualization, and large-scale spatial analysis, and should not be used as a sole basis for regulatory, legal, or operational air-quality decisions.

---

## 📚 Citation
If you use AirSat, please cite the software using the metadata provided in `CITATION.cff`.

---

## <span id="persian">🇮🇷 نسخه فارسی</span>

## 📘 معرفی
**🛰 AirSat** یک سامانه پایش آلودگی هوا مبتنی بر داده‌های ماهواره‌ای است که برای ایران توسعه داده شده است.  
این سامانه از داده‌های **Sentinel-5P (TROPOMI) سطح ۳ (OFFL)** استفاده می‌کند و امکان  
نمایش، مقایسه و دانلود آلاینده‌های جوی را از **سال ۲۰۱۸ تاکنون** فراهم می‌سازد.

🌍 **وب‌سایت:** https://attarbashian.github.io/AirSat/  
📦 **مخزن گیت‌هاب:** https://github.com/Attarbashian/AirSat  

---

## 🧪 آلاینده‌های پشتیبانی‌شده
در حال حاضر آلاینده‌های زیر در AirSat قابل مشاهده هستند:

- 🟤 دی‌اکسید نیتروژن (**NO₂**)
- 🟡 دی‌اکسید گوگرد (**SO₂**)
- ⚫ مونوکسید کربن (**CO**)
- 🔵 ازن (**O₃**)
- 🧬 فرمالدهید (**HCHO**)
- 🔥 متان (**CH₄**)
- 🌫 شاخص آئروسل فرابنفش (**UVAI**)

---

## ✨ قابلیت‌ها
- ⏱ محاسبه میانگین‌های زمانی پویا:
  - ۷ روزه
  - ۳۰ روزه
  - سه‌ماهه
  - سالانه
  - بازه زمانی دلخواه
- 🗺 تحلیل در مقیاس ملی و استانی
- 🔍 شناسایی نقاط داغ آلودگی
- 📊 نمودارهای مقایسه‌ای
- 📥 دانلود مستقیم داده‌ها:
  - فایل‌های GeoTIFF
  - تصاویر PNG
- 🌐 رابط کاربری دو‌زبانه (فارسی / انگلیسی)

---

## 🛰 منبع داده
- 🛰 ماهواره: Sentinel-5P (TROPOMI)
- 📦 سطح داده: Level-3
- ⚙ نوع پردازش: OFFL
- ☁ بستر پردازش: Google Earth Engine
- 📆 پوشش زمانی: ۲۰۱۸ تاکنون

---

## ⚠ نکات مهم
- 📐 اغلب آلاینده‌ها به‌صورت **چگالی ستونی (mol/m²)** ارائه می‌شوند.
- 🚫 تبدیل به واحدهای غلظت سطحی در این سامانه انجام نمی‌شود.
- ☁ وجود نواحی بدون داده می‌تواند به‌دلیل پوشش ابری، فیلترهای کیفی یا هندسه مدار باشد.
- 📈 افزایش بازه زمانی معمولاً پوشش فضایی را بهبود می‌دهد.

---

## 🎯 کاربرد
این سامانه برای:
- 📈 تحلیل روندها
- 🌍 مقایسه فضایی
- 🔬 مطالعات پژوهشی

> ⚖ سامانه AirSat با هدف پژوهش، نمایش و تحلیل‌های فضایی در مقیاس بزرگ توسعه یافته است و نباید به‌عنوان تنها مبنای تصمیم‌گیری‌های اجرایی، حقوقی یا مقرراتی در حوزه کیفیت هوا مورد استفاده قرار گیرد.

---

## 📚 ارجاع
اگر از AirSat استفاده می‌کنید، لطفاً نرم‌افزار را بر اساس اطلاعات ارجاع موجود در فایل `CITATION.cff` نقل‌قول کنید.

---

<br>

<p align="center">
  <b>👤 تهیه و توسعه توسط وحید عطارباشیان</b><br>
  <b>❤️ Made with love for Iran</b>
</p>
