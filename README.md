السلام عليكم 
راح اتكلم عن ادواة ال osint - جمع المعلومات   
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
 



برضو في اداة osint ثانيه مثل OSINT Framework  
مايحتاج لها شرح عشانها سهله مثلا لو تبي تختار الEmail تختارها وبتطلع لك مواقع تقدر تبحث فيها  
صوره من الاداة  
![image](https://github.com/user-attachments/assets/c679a99e-35ea-4842-8313-be6bb0e523df)

 
 الموقع المدري كم   Have I Been Pwned

موقع  قوي تقدر تستخدمها علشان تشوف اذا كان حسابك (سواء ايميلك او اسم المستخدم) تم تسريبه في تسريبات سابقة يعني اذا ايميلك تم اختراقه او تسريبه في موقع ثاني 
 صوره من الاداة 
![image](https://github.com/user-attachments/assets/cd27cdb1-e335-40bd-b03b-591f6f27a526)

 واذا نزلت تحت راح تشوف المواقع الي تسرب فيها الEmail

 


 
