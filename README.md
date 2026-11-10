# استوديو أصداء الجهة — نموذج Vivliostyle

نموذج أولي مستقل لإخراج مجلة عربية A4 باتجاه RTL. يتضمن ثماني صفحات تجريبية وقالب CSS للطباعة.

## المتطلبات
- Node.js 22.12 أو أحدث.
- npm.

## التشغيل
```bash
npm install
npm run preview
```

لإنشاء PDF:
```bash
npm run build
```
الناتج المتوقع: `dist/asdaa-aljiha-sample.pdf`

## تعديل المحتوى
- افتح `src/index.html` وعدّل العناوين والفقرات.
- استبدل كتل الصور المؤقتة بصور أصلية داخل `assets/`.
- عدّل الهوية والألوان من `styles/magazine.css`.

## الصفحات
الغلاف، الافتتاحية، ملف العدد، رصد ميداني، حوار، اقتصاد جهوي، ثقافة ومجتمع، الغلاف الخلفي.

## حدود النموذج
النصوص تجريبية وليست مواد صحفية موثقة. كتل الصور أماكن مؤقتة. لم يتم بعد اختبار PDF نهائي أو التشكيل العربي والطباعة الاحترافية. لا تعتمد الملف للطباعة التجارية قبل اختبار الخطوط وCMYK والنزف وعلامات القص ومتطلبات المطبعة.

## المراجع الرسمية
- https://docs.vivliostyle.org/en/cli/getting-started/
- https://docs.vivliostyle.org/en/cli/
- https://docs.vivliostyle.org/en/reference/supported-css-features/
