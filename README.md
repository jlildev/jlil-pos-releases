# Jlil POS — التنزيلات

هذا المستودع مخصص لملفات التركيب فقط. **الكود المصدري خاص** وليس هنا.

## أحدث إصدار

<https://github.com/jlildev/jlil-pos-releases/releases/latest>

## التثبيت

1. نزّل `Jlil.POS_<version>_x64-setup.exe` من صفحة الإصدارات.
2. شغّله. سيظهر تحذير SmartScreen لأن المثبّت غير موقّع رقمياً:
   **More info → Run anyway**.
3. اترك المسار الافتراضي وانتظر تثبيت WebView2 (بلا إنترنت).
4. شغّل **Jlil POS** من قائمة ابدأ.

## التحقق من الملف

بجانب كل مثبّت ملف `.sha256`. على Windows:

```powershell
Get-FileHash "Jlil.POS_1.2.0_x64-setup.exe" -Algorithm SHA256
```

يجب أن يطابق القيمة داخل ملف `.sha256`.
