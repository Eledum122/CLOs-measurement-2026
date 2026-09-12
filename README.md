# CLOs Measurement — Version 06

أداة Excel (مدعومة بأكواد VBA) لبناء **جدول المواصفات** وإعداد **تقرير قياس مخرجات تعلم المقرر (CLOs)**  
An Excel/VBA workbook for building the **Table of Specifications** and generating the **Course Learning Outcomes (CLOs) Assessment Report**.

**إعداد:** أ.د. حسين يوسف عبدالله العضيم — قسم الإحصاء، كلية العلوم، جامعة تبوك

---

## الملفات | Files

| الملف | الوصف |
|---|---|
| `CLOs Measurement_Version_06.xlsm` | مصنف Excel الرئيسي (Macro-Enabled) |
| `CLOsMeasurement-06-User Guide.pdf` | دليل الاستخدام المصوّر |

## المحتويات | Worksheets

`Information` · `CLOs` · `Topics` · `Activities` · `Table_Specifications` · `Exams_sheet` · `Marks` · `CLOs_Report`

## خطوات الاستخدام | Steps

1. **Information** — إدخال البيانات الأساسية للمقرر.
2. **CLOs** — إدخال نواتج التعلم، درجة كل مخرج، معيار النجاح والمستوى المستهدف.
3. **Topics** — إدخال الموضوعات وساعات الاتصال وتوزيعها على نواتج التعلم.
4. **Activities** — إدخال درجات أنشطة التقييم وتوزيعها على الموضوعات.
5. **Table_Specifications** — يتولّد جدول المواصفات تلقائيًا مع التحقق من الاتساق.
6. **Marks** — إدخال بيانات ودرجات الطلاب.
7. **CLOs_Report** — استخراج تقرير القياس (المستوى المستهدف مقابل المستوى الفعلي).

## تمكين وحدات الماكرو | Enabling Macros

1. بعد التحميل: كليك يمين على الملف ← **Properties** ← فعّل **Unblock** ← **OK**.
2. عند فتح الملف اضغط **Enable Content** في شريط التحذير الأمني.
3. عند الحاجة: `File → Options → Trust Center → Trust Center Settings → Macro Settings`.

> يعمل المصنف على Microsoft Excel لنظام Windows (2016 فأحدث). لا يُدعم تشغيل الماكرو في Excel Online.

## ملاحظات | Notes

- خلايا التحقق (`Ok` / `Error`) يجب أن تكون جميعها **Ok** قبل اعتماد جدول المواصفات.
- احتفظ بنسخة أصلية من المصنف قبل الاستخدام لكل شعبة.
- التقرير النهائي يُعتمد بالتنسيق مع منسق المقرر ولجنة الجودة بالقسم.

## الاستشهاد | Citation

> Eledum, H. Y. A. (2026). *CLOs Measurement Workbook (Version 06)*. Department of Statistics, University of Tabuk.

## الترخيص | License

للاستخدام الأكاديمي والتعليمي. يُرجى الإشارة إلى المصدر عند إعادة الاستخدام أو التعديل.
