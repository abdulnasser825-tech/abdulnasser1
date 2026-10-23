الواجهة · تطبيق تلفزيون يفتح صفحة الخبر بشاشة كاملة

1) أنشئ مستودعًا جديدًا في GitHub وارفع كل محتويات هذا المجلد (بما فيها مجلد .github).
2) من تبويب Actions شغّل "Build APK" (أو يشتغل تلقائيًا بعد الرفع).
3) بعد اكتماله نزّل الملف من Artifacts ثم فك الضغط لتحصل على app-debug.apk.
4) ثبّته: adb install app-debug.apk
5) الرابط داخل app/src/main/res/values/strings.xml (start_url).
