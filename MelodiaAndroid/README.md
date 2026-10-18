# Melodia Android shell
این پروژه نسخه Android از Web App ملودیا است و رابط وب Melodia را داخل WebView با پشتیبانی میکروفون اجرا می‌کند.

## قبل از build
در `MainActivity.kt` و `strings.xml` مقدار `https://YOUR-MELODIA-DOMAIN.example` را با دامنه واقعی Backend عوض کنید.

## Build
Android Studio را نصب کنید، پروژه را باز کنید و از Build > Generate Signed Bundle / APK خروجی AAB یا APK بگیرید.

## انتشار
برای بازار و مایکت باید حساب توسعه‌دهنده خودتان را داشته باشید و فایل امضاشده را در پنل آنها بارگذاری کنید. کلید امضا را امن نگه دارید و آن را برای کسی ارسال نکنید.

## نکته
این پروژه بدون یک Backend عمومی HTTPS قابل استفاده واقعی نیست. پروژه Flask قبلی باید روی سرور deploy شود.
