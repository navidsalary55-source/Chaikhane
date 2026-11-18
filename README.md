# بازی جذاب چای خانه

## آپلود در GitHub
1. زیپ را باز کن و **محتوای** آن را (نه خود زیپ) در مخزن آپلود کن: پوشه‌های `.github`, `www`, `docs` و فایل‌های بیرونی. فایل‌های قبلی جایگزین می‌شوند.
2. فایل‌های PNG در این پروژه نیستند (مخزن تو PNG را قفل می‌کند)؛ آیکون و اسپلش در `icon.dat` و `splash.dat` هستند.

## ساخت APK
- آزمایشی: Actions ← **Build APK** ← Run workflow.
- نهایی (برای فروشگاه): یک‌بار secret به نام `KEYSTORE_PASSWORD` بساز ← **Create keystore** ← متن `keystore.b64.txt` را secret به نام `KEYSTORE_BASE64` کن ← **Build Release APK**. فایل `.jks` و رمزش را چند جا نگه دار.

## تنظیمات داخل بازی
بالای بخش منوی `www/index.html` شیء `CFG` است: `privacy` (لینک حریم خصوصی)، `rate` و `share` (بعد از انتشار)، `ads` و `iap` (فعلاً false).
