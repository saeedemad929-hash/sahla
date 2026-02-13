# 🇪🇬 سَهلة - Sahla 
### نظام إدارة الطوابير الحكومية الذكي | Smart Government Queue System

**سَهلة** هو تطبيق موبايل متطور مبني باستخدام **Flutter**، يهدف إلى تسهيل حياة المواطنين في محافظة سوهاج وكافة أنحاء مصر من خلال رقمنة خدمات الطوابير الحكومية وتوفير كافة المعلومات اللازمة قبل الزيارة.

---

## 📸 نظرة على التطبيق (Screenshots)

<p align="center">
  <img src="https://github.com/user-attachments/assets/143b3746-5c7e-4c45-9de8-c03d98c7aee6" width="200" title="الشاشة الرئيسية">
  <img src="https://github.com/user-attachments/assets/e138e402-0245-471f-a1c8-ea58f1075ee6" width="200" title="تفاصيل الفرع">
  <img src="https://github.com/user-attachments/assets/a9beee18-2149-4174-9671-bad888f2d037" width="200" title="حجز التذكرة">
  <img src="https://github.com/user-attachments/assets/52932bad-b0b2-413a-b4e5-a9c29cb0fa38" width="200" title="التذكرة الرقمية">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/9af9d409-b71c-4f47-ae55-ab5867474000" width="200" title="الخرائط">
  <img src="https://github.com/user-attachments/assets/9b09b393-96fe-45e0-a616-591730c2db04" width="200" title="المستندات">
  <img src="https://github.com/user-attachments/assets/8194f843-a1eb-4af2-ab36-2c5ff1e3568f" width="200" title="البحث">
  <img src="https://github.com/user-attachments/assets/f9b8ca8f-d61f-4979-80b9-5da1af00dce7" width="200" title="توليد QR">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/dc212ff4-bf7b-4ffb-b790-e4ab2cb0eb02" width="200" title="واجهة المستخدم">
  <img src="https://github.com/user-attachments/assets/1dbf4fa9-3bdb-46a4-95d8-8a4775173455" width="200" title="تأكيد البيانات">
  <img src="https://github.com/user-attachments/assets/137ac782-0d8e-4898-850b-80d39ca95fd0" width="200" title="نهاية الحجز">
</p>

---

## ✨ المميزات الرئيسية (Main Features)

* 🎫 **توليد الباركود (QR Code Generation):** حجز فوري وتوليد كود رقمي لكل مواطن لتسهيل عملية الدخول.
* ⏱️ **متابعة الطابور (Live Queue Status):** معرفة عدد المنتظرين والوقت المتوقع لحظياً قبل التحرك من المنزل.
* 📍 **الربط بالخرائط (Google Maps Integration):** توجيه المواطن لأقرب فرع حكومي (مرور، سجل مدني، بريد) بدقة.
* 📄 **دليل المستندات:** عرض شامل للأوراق المطلوبة لكل خدمة حكومية لتجنب "فوت علينا بكرة".
* 🎙️ **دعم ذوي الهمم (TTS):** خاصية النطق الصوتي لأرقام التذاكر لمساعدة كبار السن وذوي الهمم.
* 📳 **نظام التنبيهات:** استخدام خاصية الاهتزاز (Vibration) لتنبيه المستخدم عند اقتراب دوره.

---

## 🛠️ التقنيات المستخدمة (Tech Stack)

* **Framework:** [Flutter](https://flutter.dev) (Dart)
* **State Management:** Provider
* **Plugins Used:**
    * `qr_flutter`: لتوليد أكواد الـ QR الديناميكية.
    * `url_launcher`: لفتح روابط الخرائط والمكالمات الهاتفية.
    * `flutter_tts`: لتحويل النص إلى كلام.
    * `vibration`: لإضافة تنبيهات حركية.
    * `google_fonts`: لتحسين الخطوط العربية (القاهرة).

---

## 🚀 طريقة التشغيل (Setup)

1. **قم بعمل Clone للمشروع:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/sahala.git](https://github.com/YOUR_USERNAME/sahala.git)
