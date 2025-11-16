# المختار الإملائي / Style Checker - أداة تصحيح الأخطاء اللغوية

<div dir="rtl">

أداة متطورة لتصحيح الأخطاء اللغوية والإملائية في النصوص العربية باستخدام واجهة رسومية حديثة.

![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)
![PyQt6](https://img.shields.io/badge/PyQt6-6.5+-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

</div>

## المميزات

- **واجهة مستخدم حديثة** مع ثيم رمادي أنيق
- **فحص تلقائي** للأخطاء اللغوية والإملائية
- **قاعدة بيانات تصحيحات شاملة** قابلة للتوسيع
- **استيراد الملفات**: دعم ملفات TXT و DOCX
- **تصدير التقارير**: تصدير النتائج كملفات نصية أو تقارير Word
- **إحصائيات مفصلة**: عرض عدد الأخطاء وأنواعها
- **واجهة عربية بالكامل** مع دعم RTL

## المتطلبات

- Python 3.7 أو أحدث
- PyQt6
- python-docx (اختياري - لاستيراد/تصدير ملفات Word)

## التثبيت

1. استنسخ المستودع:
```bash
git clone https://github.com/ayzem88/المختار-الإملائي.git
cd المختار-الإملائي
```

2. ثبت المتطلبات:
```bash
pip install -r requirements.txt
```

## الاستخدام

قم بتشغيل البرنامج:
```bash
python "0.1 أسلوبي.py"
```

### كيفية الاستخدام:

1. **تحميل ملف التصحيحات**: البرنامج يحمل `corrections.json` تلقائياً، أو يمكنك تحميل ملف آخر
2. **إدخال النص**: اكتب النص العربي أو استورد ملف TXT/DOCX
3. **فحص النص**: اضغط على زر "فحص النص" أو استخدم الاختصار `Ctrl+Return`
4. **مراجعة الأخطاء**: ستظهر الأخطاء المكتشفة في القائمة اليسرى مع التصحيحات المقترحة
5. **تصدير التقرير**: يمكنك تصدير التقرير كملف نصي أو تقرير Word

### الاختصارات:

- `Ctrl+O`: استيراد ملف TXT
- `Ctrl+S`: تصدير النتيجة
- `Ctrl+L`: تحميل ملف التصحيحات
- `Ctrl+Return`: فحص النص
- `Ctrl+Del`: مسح الكل
- `Ctrl+Q`: إغلاق البرنامج

## الملفات

- `0.1 أسلوبي.py`: الملف الرئيسي للواجهة الرسومية
- `corrections.json`: قاعدة بيانات التصحيحات (قاموس الأخطاء والتصحيحات)
- `requirements.txt`: قائمة المتطلبات
- `LICENSE`: ترخيص MIT
- `README.md`: ملف التوثيق الرئيسي

## هيكل ملف التصحيحات

ملف `corrections.json` يحتوي على قاموس بسيط:
```json
{
  "الكلمة_الخاطئة": "الكلمة_الصحيحة",
  "مثال": "مثال آخر"
}
```

يمكنك إضافة المزيد من التصحيحات بسهولة.

## المميزات التفصيلية

### فحص الأخطاء
- اكتشاف الأخطاء الإملائية واللغوية
- عرض السياق لكل خطأ
- إحصائيات عن عدد الأخطاء وتكرارها

### التصدير
- تصدير تقرير نصي بسيط
- تصدير تقرير Word منسق مع جداول

## المساهمة

نرحب بمساهماتكم! يمكنك المساهمة من خلال:

1. فتح [issue](https://github.com/ayzem88/المختار-الإملائي/issues) للإبلاغ عن مشاكل أو اقتراح ميزات جديدة
2. إرسال [pull request](https://github.com/ayzem88/المختار-الإملائي/pulls) لإضافة ميزات أو إصلاح أخطاء
3. إضافة المزيد من التصحيحات إلى `corrections.json`
4. تحسين التوثيق

## الترخيص

هذا المشروع مرخص تحت [MIT License](LICENSE) - راجع ملف LICENSE للتفاصيل.

## المطور

تم تطوير هذا المشروع بواسطة **أيمن الطيّب بن نجي** ([ayzem88](https://github.com/ayzem88))

## التواصل

للاستفسارات أو المساهمة، يمكنك التواصل معي عبر:
- البريد الإلكتروني: [aymen.nji@gmail.com](mailto:aymen.nji@gmail.com)

## ملاحظات

- البرنامج يحتاج إلى ملف `corrections.json` للعمل
- دعم ملفات DOCX يتطلب تثبيت `python-docx`
- يمكنك تخصيص ملف التصحيحات حسب احتياجاتك

## التطوير المستقبلي

- [ ] إضافة المزيد من التصحيحات إلى قاعدة البيانات
- [ ] دعم المزيد من صيغ الملفات
- [ ] إضافة اقتراحات تلقائية للتصحيحات
- [ ] تحسين خوارزمية اكتشاف الأخطاء
- [ ] إضافة واجهة سطر الأوامر (CLI)

---

# [English]

<div dir="ltr">

## Style Checker - Arabic Language Error Correction Tool

A sophisticated tool for correcting linguistic and spelling errors in Arabic texts using a modern graphical interface.

![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)
![PyQt6](https://img.shields.io/badge/PyQt6-6.5+-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## Features

- **Modern User Interface** with elegant gray theme
- **Automatic Checking** for linguistic and spelling errors
- **Comprehensive Correction Database** that can be expanded
- **File Import**: Support for TXT and DOCX files
- **Report Export**: Export results as text files or Word reports
- **Detailed Statistics**: Display number of errors and their types
- **Fully Arabic Interface** with RTL support

## Requirements

- Python 3.7 or later
- PyQt6
- python-docx (optional - for importing/exporting Word files)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/ayzem88/style-checker.git
cd style-checker
```

2. Install requirements:
```bash
pip install -r requirements.txt
```

## Usage

Run the program:
```bash
python "0.1 أسلوبي.py"
```

### How to Use:

1. **Load Correction File**: The program automatically loads `corrections.json`, or you can load another file
2. **Enter Text**: Type Arabic text or import a TXT/DOCX file
3. **Check Text**: Press the "فحص النص" button or use the shortcut `Ctrl+Return`
4. **Review Errors**: Detected errors will appear in the left list with suggested corrections
5. **Export Report**: You can export the report as a text file or Word report

### Shortcuts:

- `Ctrl+O`: Import TXT file
- `Ctrl+S`: Export result
- `Ctrl+L`: Load correction file
- `Ctrl+Return`: Check text
- `Ctrl+Del`: Clear all
- `Ctrl+Q`: Close program

## Files

- `0.1 أسلوبي.py`: Main graphical interface file
- `corrections.json`: Correction database (dictionary of errors and corrections)
- `requirements.txt`: Requirements list
- `LICENSE`: MIT License
- `README.md`: Main documentation file

## Correction File Structure

The `corrections.json` file contains a simple dictionary:
```json
{
  "incorrect_word": "correct_word",
  "example": "another example"
}
```

You can easily add more corrections.

## Detailed Features

### Error Checking
- Detection of spelling and linguistic errors
- Display context for each error
- Statistics on number of errors and their frequency

### Export
- Export simple text report
- Export formatted Word report with tables

## Contributing

We welcome contributions! You can contribute by:

1. Opening an [issue](https://github.com/ayzem88/style-checker/issues) to report problems or suggest new features
2. Submitting a [pull request](https://github.com/ayzem88/style-checker/pulls) to add features or fix bugs
3. Adding more corrections to `corrections.json`
4. Improving documentation

## License

This project is licensed under [MIT License](LICENSE) - see the LICENSE file for details.

## Developer

Developed by **Ayman Al-Tayyib Ben Naji** ([ayzem88](https://github.com/ayzem88))

## Contact

For inquiries or contributions, you can contact me via:
- Email: [aymen.nji@gmail.com](mailto:aymen.nji@gmail.com)

## Notes

- The program needs the `corrections.json` file to work
- DOCX file support requires installing `python-docx`
- You can customize the correction file according to your needs

## Future Development

- [ ] Add more corrections to the database
- [ ] Support for more file formats
- [ ] Add automatic correction suggestions
- [ ] Improve error detection algorithm
- [ ] Add command-line interface (CLI)

</div>

