---
title: Java Virtual Machine
localeTitle: Java Virtual Machine
---
# آلة جافا الافتراضية (JVM)

تنتمي Java إلى عائلة من اللغات تسمى اللغات [**المجمّعة**](https://en.wikipedia.org/wiki/Compiled_language) ( [**Compiled Languages)**](https://en.wikipedia.org/wiki/Compiled_language) . يجب تحويل أي كود مكتوب بهذه اللغة (مترجم) إلى نموذج وسيط يمكن فهمه من قبل النظام الأساسي المضيف (نظام التشغيل / النظام الأساسي الذي يتم تشغيل الكود فيه).

بالنسبة إلى Java ، يسمى هذا النموذج الوسيط **Bytecode** الذي يتم تفسيره بعد ذلك **بوقت** تشغيل يسمى Java Virtual Machine (JVM). فكر في [**JVM**](https://docs.oracle.com/javase/specs/jvms/se7/html/) كقطعة من البرامج تقوم بالعمل الشاق لتشغيل شفرة Java. فإنه يأخذ عناية من تخصيص الذاكرة ، وإدارة الخيط ، وجمع القمامة وأكثر من ذلك بكثير. وبصرف النظر عن جافا ، فإنه يدعم أيضا (قراءة: قادرة على تشغيل) رمز مكتوب بلغات مثل Groovy ، سكالا الخ

في Java ، يتم كتابة الكود وحفظه كملفات `.java` . يعمل المحول البرمجي (javac) على ملفات java ويقوم بإنشاء ملفات Bytecode ( `.class` ) المكافئة. سيكون الأمر `java` الآن قادراً على تنفيذ Bytecode المخزنة في ملفات `.class` . المزيد عن هذا لاحقا.

تصف الأقسام التالية بعض اللبنات الأساسية للتشفير في Java.