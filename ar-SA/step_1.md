سيحتاج Raspberry Pi الخاص بك إلى الاتصال بالإنترنت لتثبيت الحزم. قبل تثبيت اي حزمة ، قم بتحديث وترقية Raspbian ، نظام التشغيل لـ Raspberry Pi الخاص بك.

+ افتح نافذة طرفية وأدخل الأوامر التالية للقيام بذلك:

![افتح الوحدة الطرفية](images/terminal.png)

```bash
sudo apt-get update
sudo apt-get upgrade
```

+ الآن يمكنك تثبيت الحزم التي ستحتاج إليها عن طريق كتابة الأمر `install` في النافذة الطرفية. على سبيل المثال، إليك كيفية تثبيت برنامج Sense HAT:

```bash
sudo apt-get install sense-hat
```
