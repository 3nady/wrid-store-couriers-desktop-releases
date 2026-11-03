# وريد مناديب - Wrid Couriers — Windows installer

Installers for **Wrid Couriers** (store deliveries, dispatch and warehouse handover) on Windows 10 / 11 (64-bit). This repository holds the installers only, no source code.

## Download

**[⬇ Download WridStoreCouriers-1.0.1-x64.msi](https://github.com/3nady/wrid-store-couriers-desktop-releases/releases/download/v1.0.1/WridStoreCouriers-1.0.1-x64.msi)** (version 1.0.1)

```
https://github.com/3nady/wrid-store-couriers-desktop-releases/releases/download/v1.0.1/WridStoreCouriers-1.0.1-x64.msi
```

- All versions: [Releases](https://github.com/3nady/wrid-store-couriers-desktop-releases/releases)
- Version info as JSON (version, size, sha256, link): [latest.json](https://raw.githubusercontent.com/3nady/wrid-store-couriers-desktop-releases/main/latest.json)
- Installation guide as JSON (Arabic and English): [install-guide.json](https://raw.githubusercontent.com/3nady/wrid-store-couriers-desktop-releases/main/install-guide.json)

## Install

1. Download and double-click `WridStoreCouriers-1.0.1-x64.msi`.
2. If Windows shows "Windows protected your PC", click **More info**, then **Run anyway** (the file is not code-signed yet).
3. Click **Next** twice. On **Install options** choose "Create a desktop shortcut" (on by default) and "Start with Windows" (off by default), then **Next**, **Install**, and accept the administrator prompt.
4. Leave **Launch now** ticked and click **Finish**. The app installs to `C:\Program Files\Wrid Couriers`.
5. Sign in with the same phone number and password as the Wrid Couriers mobile app.

Silent install for many PCs (administrator Command Prompt): `msiexec /i WridStoreCouriers-1.0.1-x64.msi /qn`. Add `DESKTOP_SHORTCUT=0` to skip the desktop shortcut or `START_WITH_WINDOWS=1` to start the app with Windows.

A newer version installs over the old one and keeps the sign-in, settings and install options. When a new version is out, the app shows a notice with an **Update now** button that downloads it from here.

## التنزيل والتثبيت

**[⬇ تنزيل WridStoreCouriers-1.0.1-x64.msi](https://github.com/3nady/wrid-store-couriers-desktop-releases/releases/download/v1.0.1/WridStoreCouriers-1.0.1-x64.msi)** (الإصدار 1.0.1)

1. نزّل الملف وانقر عليه نقراً مزدوجاً.
2. إذا ظهرت رسالة «حمى Windows جهاز الكمبيوتر» اضغط «مزيد من المعلومات» ثم «تشغيل على أي حال».
3. اضغط Next مرتين. في «خيارات التثبيت» اختر «إنشاء اختصار على سطح المكتب» (مفعّل افتراضياً) و«التشغيل تلقائياً مع بدء Windows» (غير مفعّل افتراضياً)، ثم Next ثم Install، ووافق على طلب صلاحية المسؤول.
4. اترك «تشغيل البرنامج الآن» مفعّلاً واضغط Finish.
5. سجّل الدخول برقم الجوال وكلمة المرور نفسيهما المستخدمين في تطبيق وريد مناديب على الجوال.

عند صدور إصدار جديد يظهر في البرنامج تنبيه مع زر «تحديث الآن» لتنزيله من هنا، ويُثبَّت فوق الإصدار القديم مع الاحتفاظ بتسجيل الدخول والإعدادات.

الدعم عبر واتساب: +966 55 690 0966
