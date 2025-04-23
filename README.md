السلام عليكم 
راح اتكلم عن ادواة ال osint   
Shodan هذي أداة رهيبة عشان تشوف الأجهزة المتصلة بالإنترنت. مثل السيرفرات والكاميرات وحتى الأجهزة الذكية. لو تبغى تشوف إذا فيه سيرفرات معينة متصلة أو كاميرات، تقدر تستخدمها.

شلون تستخدمها؟ تدخل على الموقع https://www.shodan.io/   اذا تبي تبحث عن قواعد بيانات MySQL مفتوحة دون تأمين  port:3306 "mysql" "root" -password   او مثلا قواعد بيانات مفتوحة product:"MongoDB" port:27017 -authentication   والخ الخ اذا مو عارف تستخدم  Shodan تقدر تدخل هنا https://www.shodan.io/search/examples 




في ادواة حلوه لل osint مثل  Sherlock شنو تسوي؟
تبحث عن اسم مستخدم (Username) وتشوف وين متسجل فيه مثل تويتر-انستقرام-ريديت وغيرها 
شلون تستخدمها ؟ 
git clone https://github.com/sherlock-project/sherlock
cd sherlock
python3 sherlock lxz2

 راح تطلع لك مثل 


![image](https://github.com/user-attachments/assets/86df5828-3655-41da-958e-f2da48b7344f)
 
