# Clear-Word-ar

مكتبة `Clear-Word-ar` هي مكتبة بايثون مفتوحة المصدر تستخدم لتصفية الكلمات غير اللائقة من النصوص العربية. تهدف هذه المكتبة إلى مساعدة المطورين على تحسين محتوى النصوص عن طريق إزالة الكلمات البذيئة والإيموجيات غير المرغوبة.

## الميزات

- إزالة الإيموجيات من النصوص
- إزالة الأحرف المتكررة
- إزالة الحركات: (كل الحركات، حذف الشدة، حذف التطويل، حذف الحركة الأخيرة)
- تصفية الكلمات البذيئة مع إرجاع `True` أو `False`

## التثبيت

لتثبيت المكتبة، يمكنك استخدام الأمر التالي:

```bash
pip install clear-word-ar
```
## مثال

```
from clearAR import Word

text = "هذا النص لا يحتوي كلمات غير لائقة"

if Word.BadWord(text):
    print("النص يحتوي على كلمات غير لائقة")
else:
    print("النص خالٍ من الكلمات غير لائقة")
```
`output : النص خالٍ من الكلمات غير لائقة `

