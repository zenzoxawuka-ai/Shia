# صدى العراق — الإصدار 3.2 (R15)

معرّف البناء:
SADA-3.2-FIREBASE-INDEX-CATALOG-PAGING-20261101-R15

هذا الإصدار يعالج خطأ حجم استجابة الكتالوج عبر صفحات صغيرة، ويوضح أن فهرس orders.user يجب نشره في قواعد Firebase Realtime Database بشكل مستقل عن نشر Railway.

ملاحظة مهمة: رفع هذا ZIP إلى Railway لا ينشر database.rules.json في Firebase. يجب نشر ملف القواعد من Firebase Console > Realtime Database > Rules، مع الحفاظ على بقية القواعد وعدم فتح قراءة الطلبات للجميع.

تفاصيل الإصلاحات والقيود في RELEASE_NOTES_3.2_R15_AR.md.
