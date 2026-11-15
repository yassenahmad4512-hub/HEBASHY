# HEBASHY لنظام Android

هذا مشروع Android Studio يغلّف لعبة HEBASHY الأصلية داخل تطبيق Android باستخدام WebView. ملفات اللعبة مضمّنة داخل التطبيق، وتعمل دون اتصال بالإنترنت (تم حذف تحميل خط Google الخارجي فقط).

## استخراج APK تلقائيًا عبر GitHub

1. أنشئ مستودع GitHub جديدًا وارفع محتويات هذا المجلد إليه.
2. افتح تبويب **Actions**.
3. اختر **Build HEBASHY APK** ثم اضغط **Run workflow** (أو انتظر البناء بعد رفع الملفات إلى فرع `main`).
4. بعد نجاح البناء، افتح نتيجة التشغيل ونزّل الملف من **Artifacts** باسم `HEBASHY-APK`.
5. فك ضغط الملف وثبّت `app-debug.apk` على هاتف Android.

## البناء محليًا

افتح المجلد في Android Studio، ثم نفّذ مهمة `app > Tasks > build > assembleDebug`. يتطلب ذلك Android SDK 35 وJDK 17.
