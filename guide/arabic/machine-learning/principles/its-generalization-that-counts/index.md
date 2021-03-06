---
title: Its Generalization That Counts
localeTitle: تعميمها وهذا هو المهم
---
## تعميمها وهذا هو المهم

تأتي قوة التعلم الآلي من عدم الحاجة إلى شفرة صلبة أو صراحة تحديد المعلمات التي تصف بيانات التدريب والبيانات غير المرئية. هذا هو الهدف الأساسي للتعلم الآلي: تعميم نتائج المتعلم.

لاختبار قابلية تعميم المتعلم ، سترغب في الحصول على بيانات اختبار منفصلة مجموعة لا تستخدم بأي شكل من الأشكال في تدريب المتعلم. هذا يمكن أن تنشأ من قبل إما تقسيم كامل بيانات التدريب الخاصة بك إلى مجموعة تدريب واختبار ، أو لجمع المزيد من البيانات. إذا كان المتعلم يستخدم البيانات الموجودة في الاختبار مجموعة البيانات ، وهذا من شأنه خلق نوع من التحيز في المتعلم الخاص بك للقيام بعمل أفضل من واقع.

إحدى الطرق للحصول على فكرة عن كيفية قيام المتعلم بعمله في مجموعة بيانات الاختبار هو أداء ما يسمى **التحقق من صحة عبر** . هذا ينقسم عشوائيا بك بيانات التدريب في عدد معين من المجموعات الفرعية (على سبيل المثال ، عشر مجموعات فرعية) و يترك مجموعة فرعية واحدة بينما يتدرب المتعلم على الباقي. ثم مرة واحدة تم تدريب المتعلم ، يتم استخدام مجموعة البيانات إلى اليسار للاختبار. هذه التدريب ، وترك مجموعة فرعية واحدة ، ويتم تكرار الاختبار أثناء تدوير من خلال المجموعات الفرعية.

#### معلومات اكثر:

*   [قليل من الأشياء المفيدة التي يجب معرفتها عن تعلم الآلة](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)
*   ["كيف تستخدم مجموعة بيانات الاختبار بعد التحقق من الصحة المتصالبة"](https://stats.stackexchange.com/a/153058/132399)