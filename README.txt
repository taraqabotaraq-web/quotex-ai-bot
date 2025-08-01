# بوت إشارات Quotex AI

## طريقة التشغيل على Render:
1. ادخل https://render.com
2. أنشئ خدمة جديدة (Web Service)
3. اربطها مع مستودع GitHub الذي رفعت فيه الملفات
4. اختر Runtime: Python 3
5. في Start Command اكتب:
   python quotex_ai_bot.py
6. أضف متغيرات البيئة:
   TELEGRAM_TOKEN = توكن بوت التليجرام
   CHAT_ID = معرف الشات
7. اضغط Deploy

البوت هيبدأ يرسل إشارات على تليجرام 24 ساعة.
