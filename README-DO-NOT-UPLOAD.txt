تحديث الموقع v2 — خطوات الرفع (اقرأي قبل الرفع)
================================================

تنبيه مهم: لو عندك على الجهاز فولدرات قديمة اسمها website-update —
دي نسخ قديمة من مرة قديمة. استخدمي فولدر website-update-v2 ده بس.

المحتوى (4 ملفات هنرفعها + ملف التعليمات ده اللي مش هنرفعه):
  1) index.html          → 23,531 bytes (حوالي 23 KB)
  2) script.js           → 12,195 bytes (حوالي 12 KB)
  3) styles.css          → 51,937 bytes (حوالي 51 KB)
     التلاتة دول بيتحطوا في جذر المستودع
  4) assets/Nedaa_CV.pdf → 11,490 bytes (حوالي 11 KB)
     ده بيتحط جوه فولدر assets في المستودع

اختبري قبل الرفع (أهم خطوة):
  اعملي دبل كليك على index.html عشان يفتح في كروم.
  لازم تلاقي في أول الصفحة جملة فيها:
  Microsoft Certified Data Analyst Associate (PL-300)
  وفي آخر الصفحة لينك LinkedIn.
  لو مش لاقية PL-300 → الفولدر ده مش النسخة الجديدة، ارجعي
  نزّلي الملف المضغوط v2 من جديد.

خطوات الرفع:
  1) في جذر المستودع: Add file → Upload files
     → اسحبي index.html و script.js و styles.css
     → سيبي الاختيار Commit directly to the main branch
     → اكتبي: Update site content v2 → Commit changes
     (لو ظهر إنه هيستبدل ملفات موجودة — ده المطلوب بالظبط)
  2) ادخلي فولدر assets في المستودع: Add file → Upload files
     → اسحبي Nedaa_CV.pdf من فولدر assets اللي جوا الفولدر ده
     → اكتبي: Update CV → Commit changes
  3) استني دقيقتين، افتحي nedaaalgdawy-svg.github.io
     واعملي تحديث قوي: Ctrl + Shift + R
  4) جرّبي بنفسك:
     - أول الصفحة فيها PL-300 وفي آخرها لينك LinkedIn
     - زرار Download CV ينزل الـ CV الجديد (رقم 01115829529)
     - زرار عربي / English شغال بالنصوص الجديدة
     - امسحي كود QR من كارت الشغل وتأكدي إن الصفحة بتفتح

ملاحظة: ملف التعليمات ده README-DO-NOT-UPLOAD.txt
لا ترفعيه على GitHub — للقراءة بس.
