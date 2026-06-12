# دليل النشر الكامل — GitHub Pages لمنصة Takamul OmniPro
### بدون كشف الكود · مجاني 100% · خطوة بخطوة

---

## قبل البدء — ماذا سننشر؟

```
المستودع الخاص (موجود على Streamlit)   المستودع الجديد العام
┌──────────────────────────────┐        ┌────────────────────────────┐
│  كود المنصة الكامل           │        │  index.html  (صفحة التعريف) │
│  (لن يراه أحد أبداً)         │        │  _config.yml               │
│  يشتغل على Streamlit Cloud   │        │  sitemap.xml               │
│  https://takamul-mekky       │        │  robots.txt                │
│         .streamlit.app       │        │  llms.txt                  │
└──────────────────────────────┘        └────────────────────────────┘
                                                     ↓
                                        https://takamul-mekky.github.io
```

**المطلوب منك:** حساب GitHub فقط (مجاني).

---

## الخطوة 1 — إنشاء مستودع GitHub Pages

**1.1** افتح المتصفح واذهب إلى: `https://github.com`

**1.2** اضغط على زر **"+"** في أعلى يمين الصفحة ← ثم اضغط **"New repository"**

**1.3** في صفحة إنشاء المستودع:

| الحقل | ما تكتبه |
|---|---|
| Repository name | `takamul-mekky.github.io` |
| Description | منصة Takamul OmniPro للطاقة الشمسية |
| Public / Private | ✅ اختر **Public** |
| Initialize with README | ❌ لا تضع علامة هنا |

**1.4** اضغط الزر الأخضر: **"Create repository"**

> ⚠️ **مهم جداً:** اسم المستودع يجب أن يكون بالضبط `takamul-mekky.github.io`
> (باستخدام اسم المستخدم الخاص بك على GitHub، إذا اسمك المستخدم مختلف غيّره)

---

## الخطوة 2 — رفع الملفات الخمسة

**2.1** بعد إنشاء المستودع ستظهر لك صفحة فارغة، اضغط:
**"uploading an existing file"** (رابط باللون الأزرق في المنتصف)

**2.2** ستظهر منطقة رفع الملفات. اسحب الملفات الخمسة التالية أو اضغط "choose your files":

- ✅ `index.html`
- ✅ `_config.yml`
- ✅ `sitemap.xml`
- ✅ `robots.txt`
- ✅ `llms.txt`

**2.3** انتظر حتى تكتمل عملية الرفع (شريط أخضر لكل ملف)

**2.4** في الأسفل في خانة **"Commit changes"**:
- في الحقل الأول اكتب: `Add GitHub Pages files`
- اترك باقي الخيارات كما هي
- اضغط الزر الأخضر: **"Commit changes"**

---

## الخطوة 3 — تفعيل GitHub Pages

**3.1** في نفس المستودع اضغط على **"Settings"** (في القائمة العلوية)

**3.2** في القائمة الجانبية اليسرى، ابحث عن **"Pages"** واضغط عليها

**3.3** ستجد قسماً اسمه **"Branch"**:
- من القائمة المنسدلة اختر: **main**
- اترك المجلد: **/ (root)**
- اضغط **"Save"**

**3.4** ستظهر رسالة صفراء: *"GitHub Pages source saved"*

**3.5** انتظر من **1 إلى 3 دقائق** ثم ارفع الصفحة نفسها

**3.6** ستظهر رسالة خضراء: ✅ *"Your site is live at https://takamul-mekky.github.io"*

**3.7** اضغط على الرابط للتأكد من أن الصفحة تعمل ✓

---

## الخطوة 4 — Google Search Console (غداً أو بعده)

هذه الخطوة تجعل Google تعرف بوجود موقعك وتظهره في نتائج البحث.

**4.1** اذهب إلى: `https://search.google.com/search-console`

**4.2** اضغط **"Start now"** (إذا كنت مسجلاً بـ Google ستدخل مباشرة)

**4.3** اضغط **"Add property"** (أو إذا كانت المرة الأولى سيسألك مباشرة)

**4.4** اختر **"URL prefix"** وفي الحقل أدخل:
```
https://takamul-mekky.github.io
```
ثم اضغط **"Continue"**

**4.5** ستظهر خيارات للتحقق من الملكية، اختر **"HTML file"**:
- اضغط **"Download"** لتحميل ملف باسم مثل `google5a7b...html`
- ارفع هذا الملف على مستودع GitHub بنفس طريقة الخطوة 2
- ارجع لـ Search Console واضغط **"Verify"**
- إذا نجح التحقق ستظهر ✅ رسالة "Ownership verified"

**4.6** أضف الـ Sitemap:
- في القائمة اليسرى اضغط **"Sitemaps"**
- في الحقل اكتب: `sitemap.xml`
- اضغط **"Submit"**

> النتيجة: Google تبدأ فهرسة موقعك خلال 1–3 أسابيع

---

## الخطوة 5 — ملف llms.txt (هذا الأسبوع)

ملف `llms.txt` موجود بالفعل في الملفات التي رفعتها في الخطوة 2.
لا شيء إضافي تحتاجه — أدوات الذكاء الاصطناعي مثل ChatGPT وPerplexity وClaude ستجده تلقائياً على:
```
https://takamul-mekky.github.io/llms.txt
```

---

## الخطوة 6 — Zenodo DOI (قبل إرسال الورقة البحثية)

هذه الخطوة تمنحك رقم DOI رسمياً تضيفه كمرجع في ورقتك.

**6.1** اذهب إلى: `https://zenodo.org`

**6.2** اضغط **"Sign up"** ← اختر **"Sign up with GitHub"** (أسهل)

**6.3** بعد الدخول اضغط **"New Upload"** (زر أزرق في أعلى يمين)

**6.4** في صفحة الرفع:
- **Upload Type:** اختر **"Software"**
- **Files:** ارفع ملف `requirements.txt` فقط (أو ملف نصي وصفي)

**6.5** أكمل البيانات:

| الحقل | القيمة |
|---|---|
| Title | Takamul OmniPro: Advanced Solar PV Research & Engineering Platform |
| Authors | Abdel-baset Hofny Abdel-baset Mekky |
| Description | منصة بحثية متكاملة للطاقة الشمسية... (انسخ من README) |
| License | Other (Non-Commercial) |
| Version | v23.5.1 |
| Keywords | photovoltaic, simulation, Saudi Arabia, pvlib, machine learning, LCOE |
| Related URL | https://takamul-mekky.streamlit.app |

**6.6** اضغط **"Publish"**

**6.7** ستحصل على DOI بالشكل: `10.5281/zenodo.XXXXXXX`

أضف في ورقتك البحثية:
```
Mekky, A.-b. H. (2026). Takamul OmniPro (v23.5.1). Zenodo. https://doi.org/10.5281/zenodo.XXXXXXX
```

---

## ملخص الخطوات والروابط النهائية

| الخطوة | المدة | النتيجة |
|---|---|---|
| 1 — إنشاء مستودع | 2 دقائق | مستودع `takamul-mekky.github.io` جاهز |
| 2 — رفع الملفات | 3 دقائق | 5 ملفات على GitHub |
| 3 — تفعيل Pages | 3 دقائق + انتظار | `https://takamul-mekky.github.io` يعمل ✅ |
| 4 — Search Console | 10 دقائق | Google تفهرس الموقع خلال 1-3 أسابيع |
| 5 — llms.txt | مرفوع بالفعل | أدوات AI تتعرف على المنصة |
| 6 — Zenodo DOI | 10 دقائق | DOI رسمي للورقة البحثية |

---

## أسئلة شائعة

**❓ هل سيرى أي شخص كود المنصة؟**
لا. الكود موجود في Streamlit Cloud (مستودع خاص). هذا المستودع الجديد يحتوي على صفحة HTML تعريفية فقط.

**❓ ما اسم المستخدم الصحيح لـ GitHub؟**
اسم المستودع يجب أن يكون `USERNAME.github.io` حيث `USERNAME` هو اسم حسابك على GitHub.

**❓ لماذا الموقع لم يظهر بعد 3 دقائق؟**
انتظر 5 دقائق ثم اضغط Ctrl+Shift+R لتحديث المتصفح بشكل كامل.

**❓ هل يمكن تعديل الصفحة لاحقاً؟**
نعم، اذهب للمستودع ← اضغط على `index.html` ← اضغط أيقونة القلم ← عدّل ← Commit.

---

*دليل إعداد GitHub Pages لمنصة Takamul OmniPro · إصدار يونيو 2026*
