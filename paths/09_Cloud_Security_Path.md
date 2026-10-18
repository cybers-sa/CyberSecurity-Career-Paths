# ☁️ الأمن السحابي (Cloud Security)

> **الفكرة باختصار:** تؤمّن الأنظمة اللي تشتغل على AWS و Azure و GCP. السحابة تغيّر الأمن من حماية أجهزة إلى حماية **إعدادات وهويات وبيانات**، ومعظم الحوادث السحابية سببها إعداد خاطئ وليس اختراقًا معقدًا.

**الصعوبة:** ⭐⭐⭐⭐ · **مناسب لمن:** عنده خلفية في الشبكات أو الأنظمة أو التطوير، ويحب الأتمتة والبنية ككود

---

## 🧠 أهم فكرة: المسؤولية المشتركة

| | مزود السحابة | أنت (العميل) |
|---|---|---|
| المبنى والعتاد والمحاكاة الافتراضية | ✅ | |
| الهويات والصلاحيات | | ✅ |
| إعدادات الشبكة والتخزين | | ✅ |
| البيانات والتشفير | | ✅ (وأدوات المزود تساعدك) |
| التطبيقات والتحديثات (IaaS) | | ✅ |

كلما انتقلت من IaaS إلى PaaS إلى SaaS زادت مسؤولية المزود، لكن **الهوية والبيانات تبقى عليك دائمًا.**

---

## 👤 الأدوار الوظيفية

| الدور | وش يسوي |
|---|---|
| Cloud Security Engineer | بناء الضوابط والحواجز الأمنية في السحابة |
| Cloud Security Architect | تصميم "Landing Zone" آمنة ومعمارية متعددة الحسابات |
| CSPM / Posture Analyst | مراقبة الإعدادات الخاطئة ومعالجتها |
| Cloud SOC / Detection Engineer | كشف التهديدات في سجلات السحابة |
| DevSecOps (Cloud) | أمن خطوط النشر والبنية ككود والحاويات |
| Cloud Penetration Tester | اختبار اختراق للبيئات السحابية |
| Cloud GRC | الامتثال السحابي ([مسار GRC](./02_GRC_Path.md)) |

---

## 🗺️ خارطة الطريق

**0️⃣ المتطلبات:** الشبكات · Linux · أساسيات الهوية ([مسار IAM](./07_IAM_Path.md)) · Python/Bash · Git

**1️⃣ أساسيات السحابة:** افهم IaaS/PaaS/SaaS، المناطق والـ Availability Zones، الحسابات والاشتراكات.
👉 [AWS Cloud Practitioner](https://aws.amazon.com/certification/certified-cloud-practitioner/) أو [Microsoft AZ-900](https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/) أو [Google Cloud Digital Leader](https://cloud.google.com/learn/certification/cloud-digital-leader)

**2️⃣ اختر سحابة واحدة وتعمّق فيها** (لا تتعلم الثلاث دفعة واحدة). المبادئ تنتقل بينها. اسأل: وش تستخدم الجهات اللي أستهدفها؟

**3️⃣ ركائز الأمن السحابي:**
- **الهوية:** IAM, Roles, Policies, Least Privilege, MFA, Federation
- **الشبكة:** VPC/VNet, Security Groups, Private Endpoints, WAF
- **البيانات:** التشفير (KMS/Key Vault), إدارة المفاتيح, تصنيف البيانات
- **السجلات والكشف:** CloudTrail / Activity Log / Cloud Audit Logs ثم SIEM
- **إدارة الوضع الأمني (CSPM):** اكتشاف الإعدادات الخاطئة

**4️⃣ البنية ككود (IaC) والأتمتة:** Terraform + فحصه أمنيًا قبل النشر

**5️⃣ الحاويات و Kubernetes:** Docker ثم Kubernetes ثم أمنهما

**6️⃣ التخصص:** معماري · كشف واستجابة سحابية · هجومي · امتثال

---

## 🎓 الشهادات

### ☁️ محايدة (لا تعتمد على مزود)

| الشهادة | ملاحظات |
|---|---|
| [CCSK v5 (Cloud Security Alliance)](https://cloudsecurityalliance.org/education/ccsk) 💲 | الأنسب كبداية محايدة: اختبار مفتوح الكتاب عبر الإنترنت، 60 سؤالًا، النجاح من 80%. السعر المعلن 445$ ويشمل محاولتين. تغطي 12 مجالًا وتضيف الذكاء الاصطناعي و Zero Trust |
| [CCSP (ISC2)](https://www.isc2.org/certifications/ccsp) 💲 | متقدمة، تحتاج خبرة، ومعروفة عند أصحاب العمل |
| [CompTIA Security+](https://www.comptia.org/certifications/security) 💲 | أساس عام قبل التخصص |
| [CKS (Kubernetes)](https://training.linuxfoundation.org/certification/certified-kubernetes-security-specialist/) 💲 | أمن Kubernetes، تتطلب CKA |

### 🟧 AWS

| الشهادة | ملاحظات |
|---|---|
| [Cloud Practitioner](https://aws.amazon.com/certification/certified-cloud-practitioner/) | البداية |
| [Solutions Architect – Associate](https://aws.amazon.com/certification/certified-solutions-architect-associate/) | أساس يفيد قبل التخصص |
| [Security – Specialty (SCS-C03)](https://aws.amazon.com/certification/certified-security-specialty/) | تكلفتها 300$. لا يوجد شرط مسبق رسمي، لكن يوصى بخبرة 5 سنوات في أمن تقنية المعلومات وسنتين عمل مع AWS |

### 🟦 Microsoft Azure

| الشهادة | ملاحظات |
|---|---|
| [AZ-900](https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/) | البداية |
| [SC-900](https://learn.microsoft.com/en-us/credentials/certifications/security-compliance-and-identity-fundamentals/) | أساسيات الأمن والهوية |
| [SC-300](https://learn.microsoft.com/en-us/credentials/certifications/identity-and-access-administrator/) | الهوية. ⚠️ تتحدث نسخته الإنجليزية في 28 أكتوبر 2026 |
| [SC-200](https://learn.microsoft.com/en-us/credentials/certifications/security-operations-analyst/) | العمليات الأمنية (Sentinel / Defender). ⚠️ تتحدث نسخته الإنجليزية في 21 أكتوبر 2026 |

> 🚨 **تحديث مهم:** شهادة **Azure Security Engineer Associate (AZ-500)** أُوقفت بتاريخ **31 أغسطس 2026** ولا يمكن الحصول عليها أو تجديدها (حسب صفحة Microsoft Learn الرسمية). كثير من الشروحات على الإنترنت ما زالت تنصح بها، فتجاهلها. ركز على **SC-200 و SC-300 مع الخبرة العملية على Defender for Cloud و Sentinel.** راجع [الصفحة الرسمية](https://learn.microsoft.com/en-us/credentials/certifications/azure-security-engineer/) لمعرفة الجديد.

### 🟥 Google Cloud

| الشهادة | ملاحظات |
|---|---|
| [Cloud Digital Leader](https://cloud.google.com/learn/certification/cloud-digital-leader) | البداية |
| [Professional Cloud Security Engineer](https://cloud.google.com/learn/certification/cloud-security-engineer) | 200$، مدتها ساعتان، 50 إلى 60 سؤالًا، ويوصى بـ 3+ سنوات خبرة منها سنة على Google Cloud |

---

## 🧪 تدريب عملي (تعلّم بالتجربة)

> ⚠️ **تحذير الفواتير:** قبل أي تجربة في حساب حقيقي، فعّل **تنبيهات الميزانية (Budget Alerts)** واحذف الموارد بعد التجربة. فواتير الحساب المنسي أشهر قصة مبتدئ في السحابة!

### 🎯 تحديات أمنية (CTF سحابي)

| المنصة | الفائدة |
|---|---|
| [flaws.cloud](http://flaws.cloud) 🆓 | تحدي AWS من تصميم Scott Piper، يعلمك أخطاء الإعداد الشائعة على مراحل، وبداية ممتازة |
| [flaws2.cloud](http://flaws2.cloud) 🆓 | الجزء الثاني: هجوم ودفاع على AWS |
| [Wiz Cloud Champions](https://cloudsecuritychampionship.com) | مسابقة CTF سحابية شهرية من Wiz Research مع لوحة ترتيب (تحقق من الشروط) |
| [CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat) 🆓 | بيئات AWS ضعيفة تنشرها في حسابك |
| [Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat) 🆓 | بيئة Kubernetes ضعيفة |
| [Pwned Labs](https://pwnedlabs.io) 🆓/💲 | مختبرات اختراق سحابي واقعية |

### 📖 دورات ومختبرات رسمية

| المنصة | الفائدة |
|---|---|
| [AWS Skill Builder](https://skillbuilder.aws) 🆓/💲 | دورات وتحضير شهادات، وفيه محتوى مجاني |
| [AWS Workshops](https://workshops.aws) 🆓 | ورش تطبيقية، منها الأمن |
| [Microsoft Learn](https://learn.microsoft.com/training/) 🆓 | مسارات كاملة مجانية بمختبرات |
| [Google Cloud Skills Boost](https://www.cloudskillsboost.google) 🆓/💲 | مختبرات تفاعلية |
| [TryHackMe](https://tryhackme.com) 🆓 | غرف سحابية للمبتدئين |
| 🎓 [Azure for Students](https://azure.microsoft.com/en-us/free/students) | رصيد 100$ لمدة 12 شهرًا بدون بطاقة ائتمانية لطلاب الجامعات بعد التحقق ببريد الجامعة |
| 🎓 [AWS Educate](https://aws.amazon.com/education/awseducate/) | دورات مجانية وشارات، التسجيل بالبريد فقط (13+ سنة) |

---

## 🛠️ الأدوات

| الفئة | أدوات مجانية / مفتوحة المصدر |
|---|---|
| تدقيق الوضع الأمني (CSPM) | [Prowler](https://github.com/prowler-cloud/prowler) · [ScoutSuite](https://github.com/nccgroup/ScoutSuite) · [Steampipe](https://steampipe.io) · [Cartography](https://github.com/cartography-cncf/cartography) |
| فحص البنية ككود | [Checkov](https://www.checkov.io) · [Trivy](https://trivy.dev) · [KICS](https://kics.io) |
| الحاويات و Kubernetes | [Trivy](https://trivy.dev) · [Grype](https://github.com/anchore/grype) · [kube-bench](https://github.com/aquasecurity/kube-bench) · [Kubescape](https://kubescape.io) · [Falco](https://falco.org) |
| الأسرار | [Gitleaks](https://github.com/gitleaks/gitleaks) · [TruffleHog](https://github.com/trufflesecurity/trufflehog) |
| هجومي (بإذن فقط) | [Pacu](https://github.com/RhinoSecurityLabs/pacu) · [CloudFox](https://github.com/BishopFox/cloudfox) · [ROADtools](https://github.com/dirkjanm/ROADtools) |
| كشف وسجلات | CloudTrail + GuardDuty (AWS) · Defender for Cloud + Sentinel (Azure) · Security Command Center (GCP) · [Wazuh](https://wazuh.com) |

---

## 🏢 من الداخل: كيف تبدو بيئة السحابة في المؤسسات؟

> هذا القسم مبني على الممارسات الشائعة في المؤسسات، ويفيدك لفهم ما ستقابله في الشغل ولإجابات المقابلات. الأسماء تختلف بين المزودين لكن الفكرة واحدة.

### الصورة الكاملة (Landing Zone)

المؤسسة الناضجة **ما تشتغل في حساب واحد.** تبني هيكلًا متعدد الحسابات:

- **حسابات/اشتراكات منفصلة** لكل بيئة (إنتاج، تطوير، اختبار) ولكل فريق أو تطبيق حساس
- **حساب مركزي للأمن** يجمع السجلات من كل الحسابات (ولا أحد يقدر يحذفها)
- **سياسات وقائية على مستوى المؤسسة:** AWS Service Control Policies أو Azure Policy أو GCP Organization Policies، تمنع أخطاء مثل فتح تخزين للعامة أو إنشاء موارد خارج مناطق معينة
- **شبكة مركزية (Hub & Spoke)** مع اتصال خاص بالمقر
- **هوية موحدة** (Entra ID / AWS IAM Identity Center) مع SSO و MFA، بدل حسابات محلية متفرقة
- **وسم الموارد (Tagging)** لتحديد المالك والتصنيف والبيئة
- **حساب طوارئ (Break-glass)** محفوظ ومراقب بشدة

### الأخطاء الشائعة اللي ستقابلها (وستصلحها)

1. تخزين (S3 / Blob) مفتوح للعامة
2. مفاتيح وصول طويلة الأمد مكتوبة في الكود أو في Git
3. أدوار بصلاحيات مفرطة (`*:*`)
4. غياب MFA على الحسابات المميزة
5. تسجيل (Logging) غير مفعّل أو غير محمي
6. منافذ إدارة (SSH/RDP) مفتوحة للإنترنت
7. عدم تشفير البيانات أو إدارة المفاتيح بشكل ضعيف
8. حاويات تعمل بصلاحيات root وصور قديمة غير مفحوصة
9. بيئات التطوير مربوطة بالإنتاج
10. لا أحد يعرف مالك المورد، فلا أحد يصلحه

### ✅ قائمة ضوابط سحابية أساسية (Baseline)

- [ ] MFA إجباري لكل المستخدمين، وخصوصًا الإداريين
- [ ] لا مفاتيح وصول دائمة للبشر؛ استخدم الأدوار المؤقتة والـ SSO
- [ ] مراجعة دورية للصلاحيات (Access Review) وإزالة غير المستخدم
- [ ] تفعيل تسجيل الأنشطة الإدارية في كل الحسابات وحفظها مركزيًا
- [ ] حظر الوصول العام للتخزين على مستوى المؤسسة
- [ ] تشفير البيانات أثناء النقل والتخزين، مع إدارة مفاتيح محكمة
- [ ] إغلاق منافذ الإدارة للإنترنت، واستخدام وصول آمن (Bastion / Session Manager)
- [ ] فحص البنية ككود قبل النشر (Checkov / Trivy)
- [ ] فحص الصور والحاويات والأسرار في خط CI/CD
- [ ] مراقبة الوضع الأمني بشكل مستمر (CSPM) وتنبيه على الانحراف
- [ ] تحديد مالك لكل مورد عبر الوسوم
- [ ] نسخ احتياطي معزول وخطة استعادة مجرّبة
- [ ] خطة استجابة لحوادث سحابية (انظر [مسار الاستجابة](./05_Incident_Response_Path.md)): كيف تعزل حسابًا مخترقًا وتبطل مفاتيحه؟

### 🔭 أول 30 يومًا في وظيفة أمن سحابي

1. **افهم الخريطة:** كم حساب؟ من المالك؟ وين البيانات الحساسة؟
2. **افحص الأساسيات:** MFA، الصلاحيات المميزة، السجلات، التخزين العام
3. **شغّل أداة CSPM** (Prowler مثلًا) واكتب أول تقرير مرتب بالأولوية
4. **اكسب صداقات** مع فرق التطوير والـ DevOps؛ الأمن السحابي يفشل بدون تعاونهم
5. **اختر ٣ تحسينات سريعة الأثر** وانفذها قبل التفكير في مشاريع كبيرة

---

## الامتثال السحابي: المراجع الرسمية

| المرجع | ملاحظات |
|---|---|
| [ضوابط الأمن السيبراني للحوسبة السحابية CCC-2:2024](https://nca.gov.sa/en/regulatory-documents/controls-list/ccc/) | صادرة من الهيئة الوطنية للأمن السيبراني، وهي امتداد لضوابط ECC. تضع الحد الأدنى من المتطلبات لـ **مزودي الخدمة السحابية** و**المستفيدين منها (Tenants)**. تحديثها الأخير يعكس **متطلبات توطين البيانات** |
| [نسخة PDF من CCC-2:2024](https://cdn.nca.gov.sa/api/files/public/upload/6d5408a3-d8e6-4e96-963b-2c7198e5b7c2_CCC-2-2024-EN-.pdf) | الوثيقة الكاملة |
| [دليل تطبيق ضوابط CCC (لمزودي الخدمة)](https://cdn.nca.gov.sa/api/files/public/upload/a341fa97-dd72-476a-9ea0-2545edd1d90c_GCCC.pdf) | يشرح كيف تطبق الضوابط عمليًا |
| [ضوابط ECC-2:2024](https://nca.gov.sa/en/regulatory-documents/controls-list/ecc/) | الأساس الذي تبني عليه CCC |
| نظام حماية البيانات الشخصية (PDPL) | عبر [sdaia.gov.sa](https://sdaia.gov.sa) |
| هيئة الاتصالات والفضاء والتقنية | الإطار التنظيمي للحوسبة السحابية: [cst.gov.sa](https://www.cst.gov.sa) |
| أداة CISO Assistant | تدعم إطار CCC-1:2020 من الهيئة وتحدّث أطرها، فتفيدك للتدرب على التقييم: [GitHub](https://github.com/intuitem/ciso-assistant-community) |

> 💡 **نصيحة توظيف:** من يجمع بين مهارة سحابية + فهم عملي لـ ECC و CCC يتميز كثيرًا في سوق العمل، لأن أغلب الجهات تحتاج تطبيق الضوابط على بيئاتها السحابية فعلًا.
>
> ✍️ **تأكد دائمًا** من النسخة الحالية للضوابط ومن متطلبات قطاعك قبل الاعتماد على أي ملخص.

---

## 📚 مصادر إضافية

- [AWS Well-Architected: Security Pillar](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html)
- [CSA Cloud Controls Matrix (CCM)](https://cloudsecurityalliance.org/research/cloud-controls-matrix)
- [Microsoft Cloud Security Benchmark](https://learn.microsoft.com/en-us/security/benchmark/azure/overview)
- [CIS Benchmarks (لكل سحابة)](https://www.cisecurity.org/cis-benchmarks)
- [AWS Security Blog](https://aws.amazon.com/blogs/security/)
- [HackTricks Cloud](https://cloud.hacktricks.wiki): مرجع للهجوم على السحابة (تحقق من الرابط)

---

⬅️ [الرئيسية](../README.md) · 🏢 [أي بيئة عمل تناسب هذا المسار؟](../guides/Work_Environments_Guide.md)
