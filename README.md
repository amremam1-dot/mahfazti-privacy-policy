# 🛡️ صفحة سياسة الخصوصية لتطبيق محفظتي (Mahfazti Privacy Policy)

صفحة ويب احترافية ثنائية اللغة (عربي / إنجليزي)، متوافقة 100% مع معايير ومتطلبات **Google Play Console** و **Apple App Store Review Guidelines** لتطبيقات إدارة الأموال والمحافظ الشخصية.

---

## 🚀 كيفية رفع المشروع وتفعيله على GitHub Pages في دقيقتين

### الخطوة 1: إنشاء مستودع جديد على GitHub
1. اذهب إلى [GitHub New Repository](https://github.com/new).
2. سمّ المستودع مثلاً: `mahfazti-privacy-policy` أو `privacy-policy`.
3. اجعل المستودع **Public** (عام) لأن متجر Google Play و Apple يشترطان أن يكون الرابط متاحاً للعامة بدون تسجيل دخول.
4. لا تقم بإضافة ملف README افتراضي (لأنك سترفع هذه الملفات).
5. اضغط **Create repository**.

---

### الخطوة 2: رفع الملفات عبر Git

افتح منفذ الأوامر (Terminal أو PowerShell) في المجلد `d:\محفظتي\privacy-policy` ونفّذ الأوامر التالية (استبدل `YOUR_USERNAME` باسم حسابك على GitHub):

```bash
cd d:\محفظتي\privacy-policy

# تهيئة مستودع git محلي
git init

# إضافة الملفات
git add .
git commit -m "Initial commit: Mahfazti bilingual privacy policy page"

# تغيير اسم الفرع إلى main
git branch -M main

# ربط المستودع بحسابك على GitHub (استبدل YOUR_USERNAME و REPO_NAME)
git remote add origin https://github.com/YOUR_USERNAME/mahfazti-privacy-policy.git

# رفع الملفات
git push -u origin main
```

*(أو إذا كنت تفضل رفعها يدوياً بدون سطر أوامر: يمكنك سحب وإفلات ملف `index.html` و `README.md` مباشرة عبر زر **Upload files** في واجهة GitHub).*

---

### الخطوة 3: تفعيل GitHub Pages مجاناً

1. ادخل على صفحة المستودع على GitHub.
2. اضغط على تبويب **Settings** (الإعدادات).
3. من القائمة الجانبية اليسرى، اضغط على **Pages**.
4. تحت قسم **Build and deployment** > **Source**:
   - اختر **Deploy from a branch**.
   - اختر الفرع `main` والمجلد `/ (root)`.
   - اضغط **Save**.
5. انتظر دقيقة واحدة، وستحصل على رابط موقعك الحي مثل:
   ```
   https://YOUR_USERNAME.github.io/mahfazti-privacy-policy/
   ```

---

## 📱 إضافة الرابط في Google Play Console و Apple App Store

1. **Google Play Console:**
   - ادخل على تطبيقك > **Policy and programs** > **App content**.
   - ابحث عن **Privacy policy** واضغط **Start** أو **Manage**.
   - الصق رابط GitHub Pages واضغط **Save**.

2. **Apple App Store Connect:**
   - ادخل على تطبيقك > **App Information**.
   - في خانة **Privacy Policy URL**، الصق نفس الرابط واضغط **Save**.

---

## ✨ المميزات المدرجة في صفحة الخصوصية
- 🌍 **ثنائية اللغة (Arabic RTL / English LTR)** مع زر تبديل فوري.
- 🌓 **وضع ليلي / نهاري (Dark & Light Mode)** تلقائي مع زر تبديل يدوي.
- 📱 **متجاوبة بالكامل (Responsive)** للهواتف والشاشات الكبيرة.
- 🔒 **تغطي كافة متطلبات الأمان والتشفير:**
  - البصمة والقياسات الحيوية (Biometrics via BiometricPrompt).
  - التخزين المحلي المشفر والأوفلاين (AES-256 Offline-first).
  - المزامنة السحابية عبر Firebase.
  - سياسة إخفاء الأرقام الحساسة (Privacy Eye Shield).
  - **بند حذف البيانات والحساب (Data Deletion Request)** المطلوب إجبارياً في متجر Google Play.
