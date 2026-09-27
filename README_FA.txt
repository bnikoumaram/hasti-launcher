# Hasti Launcher

این پوشه یک Launcher مستقل برای iPhone/Home Screen است.

## فایل‌های اصلی
- index.html
- manifest.webmanifest
- favicon.ico
- icons/apple-touch-icon.png
- icons/icon-192.png
- icons/icon-512.png

## رفتار
- وقتی صفحه در Safari معمولی باز می‌شود، کاربر می‌تواند آن را Add to Home Screen کند.
- وقتی از آیکون Home Screen اجرا می‌شود، به Web App اصلی Google Apps Script هدایت می‌شود.

## لینک Web App
https://script.google.com/macros/s/AKfycbwitWA6ZuNSXAj8XJqvkD37tGmGTYuOvgp9ez-7h-a_z6IC5fwdE6eUPB2q9SLgo21vxw/exec

## روش ساده انتشار
### GitHub Pages
1. یک Repository جدید بسازید.
2. تمام محتویات این پوشه را در ریشه Repository آپلود کنید.
3. Settings → Pages
4. Source: Deploy from a branch
5. Branch: main / root
6. چند دقیقه بعد آدرس Pages را روی iPhone در Safari باز کنید.
7. Share → Add to Home Screen.

### Cloudflare Pages
همین پوشه را به عنوان Static Site منتشر کنید. Build command لازم نیست و خروجی همان ریشه پروژه است.

نکته: برای نصب آیکون، صفحه Launcher را Add to Home Screen کنید، نه لینک script.google.com.
