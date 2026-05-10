<div align="center">
  <img src="https://raw.githubusercontent.com/nikzad-avasam/downloader/refs/heads/main/dl-icon.gif" width="400" alt="wide-2" />
</div>


🎬 برای دانلود ویدیوهای یوتیوب از این پروژه استفاده کنید :‌
https://github.com/nikzad-avasam/youtube-dl


 


## ⬇️ دانلود کننده فایل + 🌐 مرورگر وب 

- ✅  دانلود کننده هر فایلی از هرکجا درون گیتهاب شما  
- ✅  پشتیبانی از فایل های بزرگ چند گیگابایتی
- 🔐 امکان رمزگذاری روی فایل های دانلود شده جهت محافظت
- ✅  استفاده از پکیج aria2 جهت دانلود بدون مشکل 
- ✅  دانلود هر نوع فایلی و فشرده سازی اتوماتیک و تحویل بصورت زیپ شده و پارت بندی شده ( هر پارت ۹۰ مگابایت )
- ✅ انجام تمام کارها بصورت خودکار و بدون نیاز به تنظیمات خاص
- ✅ پشتیبانی از دانلود همزمان چندین لینک
- ✅ امکان دسته بندی فایل های zip درون پوشه های هم نام با فایل
- ✅ امکان حذف یکجای تمام فایلهای دانلود شده 
- ✅ ذخیره سازی دائمی فایل ها در گیتهاب خودتان
- حتما بخش بروزرسانی ها را در پایین صفحه بخوانید.
- لطفا توجه کنید که برخی سرورهای ایرانی ای پی های خارج را مسدود کرده است مثلا سافت ۹۸ و امکان دانلود فایلهای آنها با استفاده از این ابزار نیست.
- 🌐 مرورگر وب اضافه شد به قسمت بروزرسانی مراجعه کنید و نحوه ی استفاده را مطلع شوید.
- 📹 آموزش ویدیویی استفاده از این ابزار به انتهای همین مطلب اضافه شد.
a
---

## 🔧 آموزش نصب

- درون این ریپازیتوری و در قسمت بالا روی دکمه ی fork بزنید.
- سپس در صورت نیاز میتوانید نام فورک را عوض کنید و در نهایت روی دکمه ی Create Fork بزنید.
- ریپازیتوری شما آماده است و اکنون میتوانید هر فایلی را که لینک دانلود آنرا دارید درون ریپازیتوری خود دانلود کنید و سپس از درون ریپازیتوری به سیستم خودتان دانلود کنید.

---

## 🎯 نحوه ی دانلود کردن فایل درون ریپازیتوری

- ۱- لینک خود را بصورت مستقیم مثل example.com/files/something.zip آماده کنید.
- ۲- به گیتهاب خود رفته و روی ریپازیتوری فورک شده بزنید و قسمت Actions را انتخاب کنید.
- ۳- در قسمت Actions شما لیست workflow ها را میبینید که یک عدد workflow داریم به اسم AVASAM - Download from URLs & Save to Repo  . روی آن بزنید و بعد از باز شدن روی Run Workflow بزنید آدرس دانلود از شما خواسته میشود و سپس شروع به دانلود .....

---


## 📂 فایلها را از کجا دانلود کنیم

همه فایلهای دانلود شده در پوشه ی downloads درون ریپازیتوری شما اضافه میشوند.فایل ها بصورت تکه های ۹۰ مگابایتی تقسیم بندی میشود مثلا اگر فایل شما ۳۰۰ مگابایت باشد باید ۴ عدد فایل دانلود شود و شما باید هر ۴ فایل را دانلود و سپس اکسترکت بکنید. برای اکسترکت کردن از 7zip استفاده کنید در لینوکس با دستور 7z x file.zip میتوانید همه ی فایل های تکه تکه را درون یک پوشه اکسترکت بکنید.
فایل اصلی دارای پسوند zip و پارت های دیگر دارای فرمت شماره گذاری شده به شکل z01 z02  و ... هستند. در ویندوز یا مک با نصب برنامه هایی مثل 7zip یا دیگر ابزارهای فشرده سازی میتوانید این فایلهای تکه تکه شده را یکجا اکسترکت بکنید.

---

## 🔔 بروزرسانی جدید: 

- امکان دسته بندی فایل های زیپ درون پوشه ها فراهم شد. اگر چندین فایل دانلود کنید و هر کدام به پارت های مختلف تقسیم بندی شوند این امکان بصورت اتوماتیک هر کدام را درون پوشه ای جدا دسته بندی میکند برای این امکان به بخش Actions رفته و روی گزینه ی Sort files بزنید و سپس گزینه ی run workflow را اجرا کنید.
- پاک کننده ی پوشه ی downloads اضافه شد در بخش Actions روی گزینه ی Clean download folder بزنید و سپس Run workflow را اجرا کنید تا پوشه ی downloads خالی شود.
- نام دانلودر در بخش Actions به Download from url تغییر پیدا کرده است.
- 🌐 مرورگر وب اضافه شد . برای استفاده از مرورگر به قسمت Actions روی گزینه ی browse web بزنید و سپس در قسمت run workflow ادرس سایت مقصد را بزنید. با این کار یک آرشیو با نام ادرس سایت و تاریخ آن لحظه ساخته میشود که درون آن اسکرین شات کامل صفحه به همراه فایل ها و لینک های صفحه قرار میگیره . همچنین فایل zip جهت دانلود در کنار پوشه ی تاریخ ساخته میشود که میتوانید یکجا دانلود کنید. یک فایل browse.md هم در مسیر اصلی ریپازیتوری اضافه میشود که شامل لیست تمام سایت هایی هست که دانلود کرده اید.


---

> راه های تکراری نتایج جدید رقم نمیزند. برای نتیجه ای جدید باید راهی جدید امتحان کرد

 
# <a href="https://avasam.ir/post/get-files-by-github" target="_blank" rel="do-follow follow sponsered">🔗 آموزش ویدیویی استفاده از این ابزار </a>

برای دریافت آموزش های بیشتر در پیام رسان بله عضو کانال ما باشید :‌
# 🔗 https://ble.ir/avasam_edu


موفق باشید.


---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

---

## فایل های دانلود شده در گیتهاب شما :

1. [Ajay.Prefix.Pro.v1.6.offline.Installer](https://github.com/PremiumHiFi/downloader/tree/main/downloads/Ajay.Prefix.Pro.v1.6.offline.Installer)

2. [LudashiPlus-v3.1.2-pre2](https://github.com/PremiumHiFi/downloader/tree/main/downloads/LudashiPlus-v3.1.2-pre2)

3. [SLPM_665.95.WE10JL - Europe League (2006 - 2007)](https://github.com/PremiumHiFi/downloader/tree/main/downloads/SLPM_665.95.WE10JL - Europe League (2006 - 2007))

4. [WinNative-PUBG-release](https://github.com/PremiumHiFi/downloader/tree/main/downloads/WinNative-PUBG-release)

5. [WinNative-PUBG-release_nova](https://github.com/PremiumHiFi/downloader/tree/main/downloads/WinNative-PUBG-release_nova)

6. [Winning Eleven 10 - Fifa World Cup Germany 2006 Edition](https://github.com/PremiumHiFi/downloader/tree/main/downloads/Winning Eleven 10 - Fifa World Cup Germany 2006 Edition)

7. [Winning Eleven 10 - Fifa World Cup Germany 2006 Edition_theta](https://github.com/PremiumHiFi/downloader/tree/main/downloads/Winning Eleven 10 - Fifa World Cup Germany 2006 Edition_theta)

8. [Winning Eleven 9 - Special Edition](https://github.com/PremiumHiFi/downloader/tree/main/downloads/Winning Eleven 9 - Special Edition)

9. [World Soccer Winning Eleven 10 %28English Patched%29](https://github.com/PremiumHiFi/downloader/tree/main/downloads/World Soccer Winning Eleven 10 %28English Patched%29)

10. [dxvk-gplasync-2.4.1-1-pre-reg](https://github.com/PremiumHiFi/downloader/tree/main/downloads/dxvk-gplasync-2.4.1-1-pre-reg)

11. [dxvk-gplasync-2.7.1-1](https://github.com/PremiumHiFi/downloader/tree/main/downloads/dxvk-gplasync-2.7.1-1)

12. [sdk36-arm64ec-2.7.1-1](https://github.com/PremiumHiFi/downloader/tree/main/downloads/sdk36-arm64ec-2.7.1-1)

13. [star-compose-v-c23d14c](https://github.com/PremiumHiFi/downloader/tree/main/downloads/star-compose-v-c23d14c)

14. [turnip-23.3.0](https://github.com/PremiumHiFi/downloader/tree/main/downloads/turnip-23.3.0)

---
