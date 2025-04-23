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

### شلون تستخدمها:
![image](https://github.com/user-attachments/assets/466d1ff1-3da0-4069-944f-80ee9b707288)

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

![image](https://github.com/user-attachments/assets/ab5c1248-0fc3-487d-9dd8-c9b562d55ec3)


تقدر تختار نوع البحث، مثل إيميل، صور، رقم، موقع، ويعطيك الأدوات المناسبة.

رابط الموقع:
[https://osintframework.com](https://osintframework.com)

---

## 4. Have I Been Pwned

**شنو يسوي؟** يفحص إذا إيميلك أو يوزرك تسرب من قبل في اختراقات.

![image](https://github.com/user-attachments/assets/efc0b18e-3028-40f4-bbd8-bae7de891a60)


### شلون تستخدمه:

1. ادخل على:
   [https://haveibeenpwned.com](https://haveibeenpwned.com)

2. حط الإيميل أو اسم المستخدم وتفحص.

إذا طلع إنه مسرب، يعني لازم تغير الباسوورد.

---

## 5. SpiderFoot — تجمع لك كل شي بروحها

**فكرتها:** أداة تجمع لك معلومات من أكثر من 100 مصدر بدون لا تسوي شي! تدور لك عن دومينات، إيميلات، IPs، مستخدمين، كل شي تقريبًا.

![image](https://github.com/user-attachments/assets/88952298-e668-4924-8efb-4ed2b6a67e4e)


### وين تفيد؟
إذا تبي تعرف كل شي عن موقع أو شخص، من غير ما تدخل كل أداة لحالها، هذي الأداة تسويها عنك أوتوماتيك.

### شلون تستخدمها:

- حملها من GitHub:
  [https://github.com/smicallef/spiderfoot](https://github.com/smicallef/spiderfoot)

- تشتغل من المتصفح، أو من التيرمنال إذا تحب الأوامر.

- إذا شغلتها، راح تعبي كل شي عن الهدف قدامك: مثل تسريبات، دومينات مرتبطة، ثغرات، ومعلومات DNS.

---

## 6. Holehe — تأكد إذا الإيميل مسجل بمواقع

**فكرتها:** تحط إيميل، وهي تدور لك وتشوف هل مستخدم في مواقع معروفة مثل تويتر، إنستقرام، فيسبوك وغيرها.

![image](https://github.com/user-attachments/assets/f97cab0d-b41d-441d-91e9-bbefcdcbdd44)


### شلون تستخدمها:

1. حملها من GitHub:
   [https://github.com/megadose/holehe](https://github.com/megadose/holehe)

2. افتح التيرمنال واكتب:
   ```bash
   holehe example@example.com
   ```
   بتطلع لك المواقع اللي هذا الإيميل مسجل فيها.

---

## 7. EmailRep — تحليل الإيميلات

**فكرتها:** تحط إيميل ويعطيك عنه معلومات إذا كان موثوق أو لا، وشنو الخدمات اللي مسجل فيها.

![image](https://github.com/user-attachments/assets/e1d96b64-06cc-456f-b6df-a7ab91e78013)


### شلون تستخدمها:

1. ادخل الموقع:
   [https://emailrep.io](https://emailrep.io)

2. أو استخدم API في سكربت خاص فيك إذا تبي شي متقدم.

---

**إعداد:** lxz2

