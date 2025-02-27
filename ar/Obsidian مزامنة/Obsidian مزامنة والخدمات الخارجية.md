[[مقدمة حول Obsidian مزامنة|Obsidian مزامنة]] هو خدمة لمزامنة الملاحظات الخاصة بك عبر الأجهزة. على الرغم من أنه يوفر ميزات مفيدة مثل [[سجل الإصدارات|استعادة الملاحظات]], إلا أنه ليس مصممًا للاستخدام كأداة للنسخ الاحتياطي للقبو الخاص بك.

على الرغم من أننا نوصيك بعمل نسخ احتياطية للقبو الخاص بك بشكل منتظم، يجب ملاحظة أن **استخدام خدمة المزامنة مع خدمات النسخ الاحتياطي الأخرى قد يؤدي إلى تلف البيانات أو فقدانها**.

إذا كنت تستخدم نفس الخدمة الخارجية على عدة أجهزة، مثل هاتفك المحمول، فأنت تعرض الخدمة للتنافس مع "Obsidian مزامنة" عندما تقوم بإجراء تغييرات على ملفاتك. يمكن أن يؤدي هذا إلى حدوث تعارضات أو تكرار الملفات أو تلفها.

لعمل نسخة احتياطية للقبو الخاص بك باستخدام خدمة خارجية، قم بتكوين الخدمة بحيث يتم إنشاء نسخ احتياطية من الجهاز الأساسي الخاص بك. على سبيل المثال، إذا كنت تقوم بمعظم كتابتك على حاسوبك المحمول، فيجب تهيئة النسخ الاحتياطي على هذا الحاسوب.

نوصي باستخدام خدمة نسخ احتياطي مخصصة لا تقوم بتحديث البيانات بشكل تلقائي على الجهاز المحلي من نسخك الاحتياطية.

> [!important] ملفات عند الطلب
> بعض خدمات التخزين السحابي، مثل OneDrive، تسمح لك بتحميل الملفات عندما تحتاج إليها وإزالتها في وقت لاحق من الجهاز المحلي لتحرير المساحة. نظرًا لأن الملفات لم تعد متاحة محليًا، يعتقد "Obsidian مزامنة" أنها تم حذفها ويقوم بإزالتها من الخادم عن بعد.
>
> لاستخدام "Obsidian مزامنة" بالاشتراك مع خاصية الملفات عند الطلب والميزات المماثلة، تأكد من تهيئة الخدمة للحفاظ على الملفات دائمًا على الجهاز.

## إزالة قبوك من خدمة المزامنة الخارجية

إذا كنت تستخدم "Obsidian مزامنة" وتدرك أنك قمت بإعداد قبوك في مجلد يتم مزامنته بواسطة خدمة تابعة لجهة خارجية، يمكنك استخدام الخطوات التالية لنقل قبوك إلى مكان أكثر أمانًا.

### إزالة من سطح المكتب

#### الخيار الأول: نقل قبوك باستخدام [[مٌحول القبو]]

1. في الزاوية السفلية اليسرى، حدد **فتح قبو آخر** (أيقونة القبو).
2. بجوار القبو الذي تريد نقله، حدد **المزيد من الخيارات** (أيقونة ثلاث نقاط).
3. حدد موقعًا جديدًا للقبو على نظام الملفات الخاص بك.

#### الخيار الثاني: نقل قبوك يدويًا

1. قم بعمل نسخ احتياطية لقبوك. انسخ مجلد القبو إلى مكان آخر لن تلمسه خلال تنفيذك لباقي الإجراءات.
2. أغلق Obsidian.
3. انقل (أو اسحب وأفلت) مجلد خزانتك من المكان القديم إلى مكان القبو الجديد الذي تم اختياره. لا تضعه في مجلد يتم مزامنته بواسطة خدمة أخرى.
4. تأكد من أن مجلد النسخ الاحتياطي يحتوي على قبوك.
5. أعد تشغيل Obsidian.
6. افتح مٌحول القبو، ثم حدد **افتح المجلد كقبو**.
7. انتقل إلى مكان القبو الجديد واختر مجلد القبو الخاص بك.
8. تحقق من أن القبو يبدو نفسه. قد تحتاج إلى إعادة تمكين [[إضافات المجتمع]] تحت **الإعدادات > إضافات المجتمع > إيقاف تشغيل الوضع المقيد**.
9. أعد ضبط "Obsidian مزامنة" مرة أخرى.

### إزالة من iOS

1. قم بعمل نسخة احتياطية لقبوك.
2. على جهازك، قم بإنشاء قبو جديد وقم بإيقاف تفعيل خيار **حفظ في iCloud Drive**.
3. قم بإغلاق تطبيق Obsidian على جميع أجهزتك لمنع عملية المزامنة من القيام بأي عملية أثناء نقل الملفات.
4. على جهاز iOS الخاص بك، افتح تطبيق Files.
5. تحت **iCloud Drive < Obsidian**، قم بالضغط على مجلد القبو الخاص بك لفترة طويلة ثم حدد **نقل**.
6. تنقل إلى **On My iPhone < Obsidian**. تأكد من أنه يمكنك رؤية القبو الذي قمت بإنشائه سابقًا.
7. اضغط على **نسخ**.
8. بعد نسخ القبو، تنقل مرة أخرى إلى **iCloud Drive < Obsidian**.
9. احذف مجلد القبو الخاص بك.

في المرة القادمة التي تفتح فيها Obsidian و مٌحول القبو، سيظهر قبوك الآن بأيقونة القبو بدلاً من السحابة، مما يشير إلى أنه لم يعد موجودًا على iCloud Drive.
