# Genius Digital — موقع ثابت (Static Site)

موقع ثنائي اللغة (عربي RTL وإنجليزي) بدون أي أدوات بناء: HTML + CSS + JavaScript فقط.
يعمل مباشرة على GitHub Pages.

## البنية
```
index.html          يحوّل الزائر إلى /ar/ أو /en/ حسب لغة متصفحه
ar/  en/            الصفحة الرئيسية + work/buildtech.html + work/hbmonitor.html
assets/             css, js, img (الشعار، الأيقونة، صورة المشاركة)
sitemap.xml  robots.txt  404.html  .nojekyll
```

## النشر على GitHub Pages
1. أنشئ مستودعًا جديدًا على GitHub (عام Public). اسمه بالضبط `aymenbech.github.io` فيعمل الموقع على الجذر مباشرة.
2. ارفع **محتويات** هذا المجلد (وليس الملف المضغوط نفسه): Add file ← Upload files ← اسحب كل الملفات والمجلدات ← Commit.
3. Settings ← Pages ← Source: **Deploy from a branch** ← Branch: `main` و Folder: `/ (root)` ← Save.
4. بعد دقيقة أو دقيقتين يظهر الرابط في نفس الصفحة.

## عنوان الموقع
تم ضبط كل الروابط (canonical وOpen Graph وsitemap) على `https://aymenbech.github.io`، لذلك **يجب أن يكون اسم المستودع بالضبط `aymenbech.github.io`**.
إذا اختلف اسم حسابك أو أردت اسم مستودع آخر، استبدل `https://aymenbech.github.io` في كل الملفات بالعنوان الصحيح (في VS Code: Ctrl+Shift+H ثم Replace All).

## دومين خاص (اختياري)
Settings ← Pages ← Custom domain، ثم اضبط سجلات DNS عند مزوّد الدومين حسب تعليمات GitHub، وفعّل Enforce HTTPS، ثم كرّر خطوة الاستبدال أعلاه.

## ما ينقص (لم يُختلق)
- لقطات شاشة المشاريع: الإطارات الحالية للهاتف بخطوط متقطعة، وتُستبدل بالصور الحقيقية.
- فيديو BuildTech وHBMonitor.
- صفحات Gifty وأهميتي وتطبيق ورشة الخياطة.
- حالة براءة HBMonitor (تُضاف شارة "براءة اختراع" فقط بعد التأكد).
- البريد الإلكتروني وحسابات التواصل الاجتماعي.
