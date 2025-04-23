# OSINT Tools - جمع معلومات

## 1. Shodan — قوقل حق الأجهزة

**فكرتها:** أداة تدور لك عن الأجهزة المتصلة بالإنترنت، مثل السيرفرات والكاميرات والراوترات.

### شلون تستخدمها:

ادخل الموقع: [https://www.shodan.io](https://www.shodan.io)

واكتب استعلام بالبحث مثل:

- عشان تدور على قواعد بيانات MySQL مفتوحة:
  ```
  port:3306 "mysql" "root" -password
  ```

- أو MongoDB بدون حماية:
  ```
  product:"MongoDB" port:27017 -authentication
  ```

ما تعرف شتكتب؟ هذا رابط فيه أمثلة جاهزة:
[https://www.shodan.io/search/examples](https://www.shodan.io/search/examples)

---

## 2. Sherlock — حق اسم المستخدم

**شنو تسوي؟** تدور لك على اسم المستخدم بكل مواقع التواصل، مثل تويتر وإنستقرام ورديت وغيرها.

![sherlock](https://github.com/user-attachments/assets/86df5828-3655-41da-958e-f2da48b7344f)

### شلون تستخدمها:

1. حمل الأداة من GitHub:
   [https://github.com/sherlock-project/sherlock](https://github.com/sherlock-project/sherlock)

2. افتح التيرمنال واكتب:
   ```bash
   python3 sherlock username
   ```
   بدال "username" حط الاسم اللي تبي تبحث عنه، وراح يطلع لك المواقع اللي مسجل فيها.

---

## 3. OSINT Framework

**فكرته:** موقع يجمع كل أدوات الـ OSINT بمكان واحد.

![osint-framework](https://github.com/user-attachments/assets/c679a99e-35ea-4842-8313-be6bb0e523df)

تقدر تختار نوع البحث، مثل إيميل، صور، رقم، موقع، ويعطيك الأدوات المناسبة.

رابط الموقع:
[https://osintframework.com](https://osintframework.com)

---

## 4. Have I Been Pwned

**شنو يسوي؟** يفحص إذا إيميلك أو يوزرك تسرب من قبل في اختراقات.

![hibp](https://github.com/user-attachments/assets/cd27cdb1-e335-40bd-b03b-591f6f27a526)

### شلون تستخدمه:

1. ادخل على:
   [https://haveibeenpwned.com](https://haveibeenpwned.com)

2. حط الإيميل أو اسم المستخدم وتفحص.

إذا طلع إنه مسرب، يعني لازم تغير الباسوورد.

---

**إعداد:** lxz2

