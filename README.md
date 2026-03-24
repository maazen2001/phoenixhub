# 🦅 Phoenix Hub — موقع الحاضنة

> **Work Better · Create More** — قطاع غزة، فلسطين

---

## 🚀 رفع الموقع على GitHub Pages — خطوة بخطوة

### الخطوة 1 — إنشاء المستودع
1. افتح [github.com](https://github.com) وسجّل دخولك
2. اضغط **New Repository** (أو زر `+` ثم **New repository**)
3. **Repository name:** `phoenix-hub` (أو أي اسم تريده)
4. اختر **Public** ✅
5. لا تضع ✓ في "Add a README file"
6. اضغط **Create repository**

---

### الخطوة 2 — رفع الملفات
1. في صفحة المستودع الجديد، اضغط **uploading an existing file**
2. ارفع **جميع الملفات** من هذا المجلد:
   ```
   index.html       ← الملف الرئيسي
   logo.jpeg        ← شعار الموقع
   _config.yml      ← إعدادات GitHub Pages
   .nojekyll        ← منع معالجة Jekyll
   data/
     └── site-data.json   ← بيانات الموقع
   ```
3. اضغط **Commit changes**

---

### الخطوة 3 — تفعيل GitHub Pages
1. اذهب إلى **Settings** في المستودع
2. من القائمة الجانبية اختر **Pages**
3. تحت **Source** اختر:
   - Branch: `main`
   - Folder: `/ (root)`
4. اضغط **Save**
5. انتظر دقيقة ← ستظهر رسالة:
   > ✅ Your site is published at `https://USERNAME.github.io/phoenix-hub/`

---

### الخطوة 4 — تفعيل نموذج التواصل (مهم!)

⚠️ **لازم تعملها قبل ما تستخدم النموذج:**

1. **افتح ملف `index.html`** في أي محرر نصوص
2. ابحث عن السطر:
   ```js
   const CONTACT_EMAIL = 'YOUR_EMAIL@gmail.com';
   ```
3. **استبدل** `YOUR_EMAIL@gmail.com` بإيميل الحاضنة الحقيقي، مثلاً:
   ```js
   const CONTACT_EMAIL = 'phoenixhub@gmail.com';
   ```
4. احفظ الملف وارفعه مرة أخرى على GitHub

5. **أول مرة** بعد الرفع:
   - افتح الموقع
   - اذهب لقسم **تواصل معنا**
   - أرسل رسالة تجريبية
   - ستصل رسالة من FormSubmit لإيميلك → **اضغط Confirm**
   - ✅ بعدها كل الرسائل تصل مباشرة للإيميل!

---

## 🔐 لوحة التحكم

| المعلومة | القيمة |
|---------|--------|
| **الوصول** | اضغط `ccc` في فوتر الموقع الرئيسي |
| **اسم المستخدم** | `mezoo` |
| **كلمة السر** | `2001` |

**لوحة تحكم Phoenix Media:**

| المعلومة | القيمة |
|---------|--------|
| **الوصول** | اضغط `ccc` في فوتر صفحة Phoenix Media |
| **اسم المستخدم** | `mezoo` |
| **كلمة السر** | `2001` |

---

## 📁 هيكل الملفات

```
phoenix-hub/
├── index.html          ← الموقع كاملاً (SPA)
├── logo.jpeg           ← شعار Phoenix Hub
├── _config.yml         ← إعدادات GitHub Pages
├── .nojekyll           ← منع Jekyll
├── data/
│   └── site-data.json  ← بيانات الموقع (للـ GitHub Sync)
└── README.md           ← هذا الملف
```

---

## 🔄 GitHub Sync (حفظ البيانات على السيرفر)

لتفعيل حفظ بيانات لوحة التحكم على GitHub مباشرة:

1. من **GitHub → Settings → Developer settings → Personal access tokens → Tokens (classic)**
2. اضغط **Generate new token**
3. اختر صلاحيات: `repo` ✅
4. انسخ الـ Token
5. في لوحة التحكم → **GitHub Sync** → أدخل:
   - اسم المستخدم على GitHub
   - اسم المستودع: `phoenix-hub`
   - الـ Token

---

## 🛠 تعديل الإيميل في لوحة التحكم

يمكنك تغيير إيميل استقبال الرسائل مباشرة من لوحة التحكم:
- **لوحة التحكم → الإعدادات → قسم التواصل → ✉️ البريد**

> ⚠️ التغيير من لوحة التحكم يحدّث العرض فقط.
> لتغيير الإيميل الذي تصله الرسائل عدّل `CONTACT_EMAIL` في `index.html`

---

## 📞 الدعم الفني

- **Phoenix Hub** — قطاع غزة، فلسطين
- Made with ❤️ for Gaza
