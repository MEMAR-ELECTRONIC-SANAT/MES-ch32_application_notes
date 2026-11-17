<p align="center"><img src="Images/GitHub-Assets/MES-Divider.svg" width="100%" alt="MES Divider"></p>

<p align="center"><img src="Images/GitHub-Assets/MES-Hero-Banner.svg" width="100%" alt="معمار الکترونیک صنعت | MEMAR ELECTRONIC SANAT"></p>

<div dir="rtl" align="right">

# یادداشت‌های کاربردی به **زبان فارسی** برای میکروکنترلرهای WCH CH32 / WCH CH32 Application Notes

</div>

[🇮🇷 فارسی](README.md) · [🇬🇧 English](README_EN.md) · [🇨🇳 اسناد اصلی چینی / Original Chinese](README_zh.md)

<div dir="rtl" align="right">

## معرفی مخزن / Repository Overview

</div>

<div dir="rtl" align="right">

این مخزن مجموعه‌ای از یادداشت‌های کاربردی (Application Notes یا AN) برای میکروکنترلرهای **WCH CH32** است. اسناد، راهنمای عملی برای قابلیت‌های MCU، طراحی سخت‌افزار، پیکربندی Firmware، راه‌اندازی Peripheralها، عیب‌یابی و بهینه‌سازی ارائه می‌کنند. این مطالب مکمل Datasheet و Reference Manual هستند و جایگزین آن‌ها نیستند.

</div>

<div dir="ltr" align="left">

This repository collects Application Notes (ANs) for **WCH CH32 microcontrollers**, covering MCU features, hardware design, firmware configuration, peripheral bring-up, debugging, and optimization. These notes complement, but do not replace, the relevant datasheets and reference manuals.

</div>

<p align="center"><img src="Images/GitHub-Assets/MES-Project-Card.svg" width="100%" alt="MES CH32 Application Notes Project Card"></p>

<div dir="rtl" align="right">

## ساختار و زبان‌ها / Structure and Languages

</div>

<div dir="rtl" align="right">

- `fa/`: راهنماهای دوزبانه فارسی و انگلیسی / Bilingual Persian-English guides.

</div>
<div dir="rtl" align="right">

- `zh/`: اسناد اصلی چینی WCH / Original WCH Chinese documents.

</div>
<div dir="rtl" align="right">

- `Images/GitHub-Assets/`: دارایی‌های گرافیکی MES / MES visual assets.

</div>
<div dir="rtl" align="right">

- `Index.csv`: نمایه اسناد / Document index.

</div>

<div dir="rtl" align="right">

## راهنمای استفاده / How to Use

</div>

<div dir="rtl" align="right">

1. شناسه یا موضوع را در جدول بیابید. / Find the required topic or AN ID in the table.

</div>
<div dir="rtl" align="right">

2. راهنمای دوزبانه را برای وضعیت ترجمه و فایل‌های موجود باز کنید. / Open the bilingual guide for translation status and available files.

</div>
<div dir="rtl" align="right">

3. PDF برای مطالعه آفلاین و HTML برای مرورگر است؛ فقط فایل‌های موجود پیوند داده می‌شوند. / Use PDF for offline reading and HTML for browser viewing; only existing files are linked.

</div>
<div dir="rtl" align="right">

4. مدل MCU، پکیج، Revision و محدودیت‌های الکتریکی را با Datasheet و Reference Manual تطبیق دهید. / Verify the MCU, package, revision, and electrical limits against the datasheet and reference manual.

</div>
<div dir="rtl" align="right">

5. کد نمونه را با نسخه MounRiver Studio (MRS)، کتابخانه و سخت‌افزار خود آزمایش کنید. / Validate examples with your MRS version, libraries, and target hardware.

</div>

<div dir="rtl" align="right">

## فهرست یادداشت‌ها / Application Notes Index

</div>

| ID | عنوان فارسی | English title | راهنمای دوزبانه / Bilingual guide | سند اصلی / Source |
|---|---|---|---|---|
| AN01000 | یادداشت کاربردی مصرف کم | Low-Power Application Note | [راهنما / Guide](fa/AN01000/README.md) | [Source](zh/AN01000/AN01000.md) |
| AN01001 | تغذیه خارجی VDD12 | External VDD12 Power Supply | [راهنما / Guide](fa/AN01001/README.md) | [Source](zh/AN01001/AN01001.md) |
| AN01002 | راهبردهای کاهش توان در CH32L103 | Power-Reduction Strategies for CH32L103 | [راهنما / Guide](fa/AN01002/README.md) | [Source](zh/AN01002/AN01002.md) |
| AN01003 | تحلیل علت‌های Reset تراشه | MCU Reset-Cause Analysis | [راهنما / Guide](fa/AN01003/README.md) | [Source](zh/AN01003/AN01003.md) |
| AN03000 | راهنمای استفاده از ICache در CH32H417 | Using ICache on CH32H417 | [راهنما / Guide](fa/AN03000/README.md) | [Source](zh/AN03000/AN03000.md) |
| AN03001 | تخصیص وقفه و بیدارسازی تراشه‌های دو هسته‌ای | Interrupt Allocation and Wake-Up on Dual-Core MCUs | [راهنما / Guide](fa/AN03001/README.md) | [Source](zh/AN03001/AN03001.md) |
| AN03002 | معرفی CoreMark و تنظیمات امتیازدهی | CoreMark Introduction and Benchmark Configuration | [راهنما / Guide](fa/AN03002/README.md) | [Source](zh/AN03002/AN03002.md) |
| AN03003 | دستورهای ویژه هسته QingKe RISC-V | QingKe RISC-V Core Special Instructions | [راهنما / Guide](fa/AN03003/README.md) | [Source](zh/AN03003/AN03003.md) |
| AN03004 | مقایسه سرعت اجرا در حافظه‌های مختلف | Execution-Speed Comparison Across Memory Types | [راهنما / Guide](fa/AN03004/README.md) | [Source](zh/AN03004/AN03004.md) |
| AN03005 | قابلیت‌های ویژه هسته در CH32H417 | Special Core Features of CH32H417 | [راهنما / Guide](fa/AN03005/README.md) | [Source](zh/AN03005/AN03005.md) |
| AN08000 | نکات DMA در سری CH32H417/415/416 | DMA Considerations for CH32H417/415/416 | [راهنما / Guide](fa/AN08000/README.md) | [Source](zh/AN08000/AN08000.md) |
| AN09000 | استفاده و نکات ADC در MCUهای عمومی | ADC Usage and Design Notes for General-Purpose MCUs | [راهنما / Guide](fa/AN09000/README.md) | [Source](zh/AN09000/AN09000.md) |
| AN09001 | راهنمای استفاده از ADC در CH32X315 | Using the ADC on CH32X315 | [راهنما / Guide](fa/AN09001/README.md) | [Source](zh/AN09001/AN09001.md) |
| AN10000 | راهنمای کاربردی صفحه‌کلید لمسی WCH | WCH Touch-Keypad Application Guide | [راهنما / Guide](fa/AN10000/README.md) | [Source](zh/AN10000/AN10000.md) |
| AN11000 | مقایسه و کاربرد RTC/Systick/TIM/LPTIM | RTC/Systick/TIM/LPTIM Comparison and Applications | [راهنما / Guide](fa/AN11000/README.md) | [Source](zh/AN11000/AN11000.md) |
| AN11001 | عملکرد و کاربرد تایمرهای کم‌حجم | Low-Power Timer Operation and Applications | [راهنما / Guide](fa/AN11001/README.md) | [Source](zh/AN11001/AN11001.md) |
| AN11002 | نکات TIM در کاربردهای موتور | TIM Considerations for Motor Applications | [راهنما / Guide](fa/AN11002/README.md) | [Source](zh/AN11002/AN11002.md) |
| AN14000 | آموزش پایه استفاده از SerDes | SerDes Fundamentals and Usage | [راهنما / Guide](fa/AN14000/README.md) | [Source](zh/AN14000/AN14000.md) |
| AN16001 | مقایسه I2C و I3C و راهنمای I3C | I2C and I3C Comparison and I3C Guide | [راهنما / Guide](fa/AN16001/README.md) | [Source](zh/AN16001/AN16001.md) |
| AN17000 | راهنمای استفاده از SPI Host و NSS | Using SPI Host and NSS | [راهنما / Guide](fa/AN17000/README.md) | [Source](zh/AN17000/AN17000.md) |
| AN21000 | راهنمای استفاده از SDIO در حالت Slave | Using SDIO in Slave Mode | [راهنما / Guide](fa/AN21000/README.md) | [Source](zh/AN21000/AN21000.md) |
| AN22000 | کارت چندرسانه‌ای SDMMC و ارتباط در حالت Slave | SDMMC Card and Slave-Mode Communication | [راهنما / Guide](fa/AN22000/README.md) | [Source](zh/AN22000/AN22000.md) |
| AN23000 | معرفی عملکرد و استفاده از PIOC | PIOC Features and Usage | [راهنما / Guide](fa/AN23000/README.md) | [Source](zh/AN23000/AN23000.md) |
| AN24000 | راهنمای استفاده از OPA در سری عمومی CH32 | Using OPA on General-Purpose CH32 MCUs | [راهنما / Guide](fa/AN24000/README.md) | [Source](zh/AN24000/AN24000.md) |
| AN24001 | راهنمای استفاده از CMP در سری عمومی CH32 | Using CMP on General-Purpose CH32 MCUs | [راهنما / Guide](fa/AN24001/README.md) | [Source](zh/AN24001/AN24001.md) |
| AN25001 | مقایسه SAI و I2S و راهنمای SAI | SAI and I2S Comparison and SAI Guide | [راهنما / Guide](fa/AN25001/README.md) | [Source](zh/AN25001/AN25001.md) |
| AN26001 | مقایسه SPI و QSPI و راهنمای QSPI | SPI and QSPI Comparison and QSPI Guide | [راهنما / Guide](fa/AN26001/README.md) | [Source](zh/AN26001/AN26001.md) |
| AN29000 | آموزش پایه درایور SDRAM با FMC | FMC-Based SDRAM Driver Fundamentals | [راهنما / Guide](fa/AN29000/README.md) | [Source](zh/AN29000/AN29000.md) |
| AN31001 | راهنمای استفاده از فیلتر دیجیتال در CH32H417 | Using the Digital Filter on CH32H417 | [راهنما / Guide](fa/AN31001/README.md) | [Source](zh/AN31001/AN31001.md) |
| AN35000 | مقایسه ARGB و آموزش پایه | ARGB Comparison and Fundamentals | [راهنما / Guide](fa/AN35000/README.md) | [Source](zh/AN35000/AN35000.md) |
| AN36000 | راهنمای استفاده از PSRAM | PSRAM Usage Guide | [راهنما / Guide](fa/AN36000/README.md) | [Source](zh/AN36000/AN36000.md) |
| AN36001 | اجرای کد در PSRAM | Executing Code from PSRAM | [راهنما / Guide](fa/AN36001/README.md) | [Source](zh/AN36001/AN36001.md) |
| AN36002 | انتقال LVGL به V467 و راه‌اندازی نمایشگر با PSRAM | Porting LVGL to V467 and Driving a Display with PSRAM | [راهنما / Guide](fa/AN36002/README.md) | [Source](zh/AN36002/AN36002.md) |
| AN37000 | استفاده از USB PD و مقایسه تراشه‌ها | USB PD Usage and MCU Comparison | [راهنما / Guide](fa/AN37000/README.md) | [Source](zh/AN37000/AN37000.md) |
| AN90000 | راهنمای برد توسعه CH32H417QEU-R1-1v1 | CH32H417QEU-R1-1v1 Development Board Guide | [راهنما / Guide](fa/AN90000/README.md) | [Source](zh/AN90000/AN90000.md) |
| AN90001 | توسعه WCHGUI سبک؛ نمونه کنترل‌باکس | Lightweight WCHGUI Development: Control-Box Example | [راهنما / Guide](fa/AN90001/README.md) | [Source](zh/AN90001/AN90001.md) |
| AN90002 | استفاده از ناحیه کاربر به‌عنوان DataFlash | Using the User Area as DataFlash | [راهنما / Guide](fa/AN90002/README.md) | [Source](zh/AN90002/AN90002.md) |
| AN90003 | انتقال فایل‌سیستم FatFS به MRS | Porting the FatFS File System to MRS | [راهنما / Guide](fa/AN90003/README.md) | [Source](zh/AN90003/AN90003.md) |
| AN91000 | تنظیمات و نکات عیب‌یابی تراشه‌های دو هسته‌ای | Dual-Core MCU Configuration and Debugging | [راهنما / Guide](fa/AN91000/README.md) | [Source](zh/AN91000/AN91000.md) |
| AN91001 | راهنمای استفاده از پروگرامر آفلاین | Offline Programmer Usage Guide | [راهنما / Guide](fa/AN91001/README.md) | [Source](zh/AN91001/AN91001.md) |
| AN91002 | پیکربندی فایل‌های LD و Startup | LD and Startup File Configuration | [راهنما / Guide](fa/AN91002/README.md) | [Source](zh/AN91002/AN91002.md) |
| AN91003 | فرایند LINK برای دانلود در FLASH خارجی | LINK Process for Programming External FLASH | [راهنما / Guide](fa/AN91003/README.md) | [Source](zh/AN91003/AN91003.md) |
| AN91004 | نکات کاربردی LINK و MRS | Practical LINK and MRS Notes | [راهنما / Guide](fa/AN91004/README.md) | [Source](zh/AN91004/AN91004.md) |
| AN91005 | روش عیب‌یابی از طریق خط فرمان | Command-Line Debugging | [راهنما / Guide](fa/AN91005/README.md) | [Source](zh/AN91005/AN91005.md) |
| AN91006 | تشخیص مشکلات تراشه هنگام Debug | Diagnosing MCU Issues During Debug | [راهنما / Guide](fa/AN91006/README.md) | [Source](zh/AN91006/AN91006.md) |
| AN93000 | مقایسه رابط‌های راه‌اندازی نمایشگر | Display-Interface Comparison | [راهنما / Guide](fa/AN93000/README.md) | [Source](zh/AN93000/AN93000.md) |
| AN94000 | معرفی M030 برای تغذیه و کاربردهای موتور | M030 Introduction for Power and Motor Applications | [راهنما / Guide](fa/AN94000/README.md) | [Source](zh/AN94000/AN94000.md) |
| AN94001 | نکات مرتبط با EMI | EMI Considerations | [راهنما / Guide](fa/AN94001/README.md) | [Source](zh/AN94001/AN94001.md) |
| AN97000 | ارتقای Firmware از طریق CH32 USB DFU | Firmware Upgrade via CH32 USB DFU | [راهنما / Guide](fa/AN97000/README.md) | [Source](zh/AN97000/AN97000.md) |

<div dir="rtl" align="right">

## نکات فنی / Engineering Notes

</div>

<p align="center"><img src="Images/GitHub-Assets/MES-Status-Strip.svg" width="100%" alt="MES Documentation Status"></p>

<div dir="rtl" align="right">

- Application Note جایگزین Datasheet، Reference Manual، Errata یا مستندات رسمی ابزار نیست. / An Application Note does not replace datasheets, reference manuals, errata, or official tool documentation.

</div>
<div dir="rtl" align="right">

- اعداد، واحدها، کلاک، حافظه، تغذیه، USB، RF و EMI را مستقل اعتبارسنجی کنید. / Independently validate values, units, clocks, memory, power, USB, RF, and EMI.

</div>
<div dir="rtl" align="right">

- پیش از استفاده در محصول، طراحی را روی سخت‌افزار واقعی آزمایش کنید. / Test the design on real hardware before production use.

</div>
<div dir="rtl" align="right">

- برای گزارش خطا، شناسه AN، مدل MCU، نسخه ابزار و مراحل بازتولید را درج کنید. / Include the AN ID, MCU model, tool version, and reproduction steps when reporting issues.

</div>

<div dir="rtl" align="right">

## منابع / Resources

</div>

<div dir="ltr" align="left">

- [WCH](https://www.wch.cn/) · [WCH Forum](https://www.wch.cn/bbs/forum-106-1.html)

</div>
<div dir="rtl" align="right">

- [راهنماهای دوزبانه / Bilingual guides](fa/) · [اسناد چینی / Chinese sources](zh/)

</div>

<div dir="rtl" align="right">

## تصاویر و دیاگرام‌های راهنما / Images and Diagrams

</div>

<div dir="rtl" align="right">

- [دارایی‌های گرافیکی MES / MES visual assets](Images/GitHub-Assets/)

</div>
<div dir="rtl" align="right">

- [بنر معرفی / Hero banner](Images/GitHub-Assets/MES-Hero-Banner.svg)

</div>
<div dir="rtl" align="right">

- [کارت پروژه / Project card](Images/GitHub-Assets/MES-Project-Card.svg)

</div>
<div dir="rtl" align="right">

- [سربرگ بخش / Section header](Images/GitHub-Assets/MES-Section-Header.svg)

</div>
<div dir="rtl" align="right">

- [نوار وضعیت / Status strip](Images/GitHub-Assets/MES-Status-Strip.svg)

</div>
<div dir="rtl" align="right">

- [تصویر پایانی / Thank-you footer](Images/GitHub-Assets/MES-Thank-You-Footer.svg)

</div>

<div dir="rtl" align="right">

## تهیه و تدوین / Credits

</div>

<p align="center"><img src="Images/GitHub-Assets/MES-Thank-You-Footer.svg" width="100%" alt="Thank you for using MES resources"></p>

<div dir="rtl" align="right">

<div dir="rtl" align="right">

**معمار الکترونیک صنعت**  

</div>

</div>
<div dir="ltr" align="left">

**MEMAR ELECTRONIC SANAT (MES)**

</div>

<div dir="rtl" align="right">

<div dir="rtl" align="right">

همراه شما در مسیر طراحی و ساخت مدارهای مطمئن  

</div>

</div>
<div dir="ltr" align="left">

*Your partner in designing and building reliable circuits.*

</div>

<div dir="ltr" align="left">

- Telegram: https://t.me/Memar_Electronic

</div>
<div dir="ltr" align="left">

- Instagram: https://www.instagram.com/Memar.Electronic

</div>
<div dir="ltr" align="left">

- GitHub: https://github.com/MEMAR-ELECTRONIC-SANAT

</div>

<p align="center">
  <img src="Images/GitHub-Assets/MES_Animated_Logo_640x480.svg" width="140" alt="MES Animated Logo">
</p>
