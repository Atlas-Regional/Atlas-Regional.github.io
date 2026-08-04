# أطلس الإقليمية — GitHub Pages

موقع تعريفي لشركة أطلس الإقليمية لتوريد الأمصال والأدوية البيطرية.

## خطوات إضافة الشعار
1. احفظ صورة الشعار (الشعار الأخضر الدائري) باسم `logo.png`.
2. ضعها داخل مجلد `assets/img/` في هذا المشروع (استبدل الملف الموجود إن وجد).
3. الأبعاد المثالية: مربعة، خلفية شفافة (PNG)، لا يقل العرض عن 400px.

## خطوات إضافة صور المنتجات
الصفحة تعرض صورة لكل منتج، وإذا لم تُوجد الصورة تظهر أيقونة بديلة تلقائياً (لن تتعطل الصفحة).
لإضافة الصور الحقيقية: احفظ صورة نظيفة للمنتج (العبوة/القارورة فقط بدون إضافات تصميمية كثيرة) بصيغة `.jpg` وبنفس الاسم بالضبط، وضعها داخل `assets/img/products/`.

**منتجات HIPRA:**
- `hipradog-dhlp.jpg`
- `hipraviar-clon.jpg`
- `hipraviar-clon-h120.jpg`
- `hipragumboro-ch80.jpg`
- `hipragumboro-gm97.jpg`
- `avisan-multi.jpg`
- `toxipra-plus.jpg`

**منتجات PDN:**
- `liva.jpg`
- `oldenbent-plus.jpg`
- `optiprex.jpg`
- `electra.jpg`
- `pdn-b-complex.jpg`
- `organisch-eselen.jpg`
- `pdn-ad3e.jpg`
- `pdn-abk.jpg`
- `pdn-c100.jpg`
- `pdn-eselen20.jpg`
- `pdn-k3.jpg`
- `texara.jpg`

## رفع الموقع على GitHub Pages
```bash
git add .
git commit -m "Add company website"
git push origin main
```
ثم من إعدادات المستودع على GitHub:
`Settings > Pages > Source > Deploy from a branch` واختر الفرع `main` والمجلد `/ (root)`.

سيكون الموقع متاحاً على:
`https://<username>.github.io/<repo-name>/`
