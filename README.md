# ORIFA — Website

إعادة بناء موقع Orifa (النسخة الأصلية على Canva) كموقع ثابت بـ HTML5 / CSS3 / Vanilla JS،
جاهز للرفع مباشرة على GitHub Pages.

## البنية

```
index.html
style.css
script.js
assets/
  logo-orifa.png     شعار Orifa الذهبي (خلفية شفافة)
  ornament.png       الزخرفة الذهبية أعلى بطاقات الدورات
  hero-banner.jpg    بانر الهيرو العاجي
  about-banner.jpg   بانر قسم "عن Orifa" الأخضر الغامق
  services-bg.jpg    خلفية قسم الخدمات (أكواريل)
  courses-lily.jpg   خلفية قسم الدورات (الزنبقة)
  footer-bg.jpg      خلفية قسم التواصل
```

## الرفع على GitHub Pages

1. أنشئي repository جديد باسم `orifa` (أو أي اسم).
2. ارفعي محتويات هذا المجلد كما هي في الجذر (وليس داخل مجلد فرعي).
3. Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / `(root)` → Save.
4. الرابط سيكون: `https://<username>.github.io/orifa/`

لا يحتاج الموقع أي backend ولا build step ولا سيرفر محلي.

## ملاحظات

- الخطوط الحالية من Google Fonts كبدائل مؤقتة (Cormorant Garamond / Playfair Display / Almarai / Changa).
  عند توفر ملفات MediaPro و Stazin: ضعيها في `assets/fonts/` وأضيفي `@font-face` في أعلى `style.css`،
  ثم بدّلي قيم `--font-*`.
- أيقونات الخدمات مرسومة SVG داخل `index.html` ويمكن استبدالها بملفات مُصدّرة من Canva.
- الألوان معرّفة كمتغيّرات CSS في `:root` أعلى `style.css`.
