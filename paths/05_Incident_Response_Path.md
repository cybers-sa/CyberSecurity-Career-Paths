# ⚠️ الاستجابة للحوادث (Incident Response)

> **الفكرة باختصار:** لما يقع الاختراق فعلًا، أنت اللي تحتويه، تفهم وش صار، تطرد المهاجم، وتعيد الأمور لطبيعتها، وتتعلم منه.

**الصعوبة:** ⭐⭐⭐⭐ · **مناسب لمن:** يشتغل تحت الضغط ويحب التحقيق، ومستعد للاستدعاء خارج الدوام

---

## 👤 الأدوار الوظيفية

| الدور | وش يسوي |
|---|---|
| Incident Responder / Handler | قيادة التعامل مع الحادثة من الاكتشاف للتعافي |
| DFIR Analyst | تحقيق تقني عميق في الأجهزة والذاكرة والسجلات |
| Threat Hunter | بحث استباقي عن مهاجم لم يُكتشف بعد |
| Malware Analyst | تحليل العينات الخبيثة |
| IR Consultant | استجابة للعملاء كطرف خارجي (شركات الاستشارات) |

---

## 🔄 دورة الاستجابة

اتبع منهجية موثقة وليس اجتهادًا. المرجع الأساسي: [NIST SP 800-61](https://csrc.nist.gov/pubs/sp/800/61/r3/final).
المراحل العملية: **الاستعداد ← الكشف والتحليل ← الاحتواء ← الاستئصال ← التعافي ← الدروس المستفادة.**

📋 جاهز للاستخدام: [Incident Response Playbooks](https://www.incidentresponse.com/playbooks/)

---

## 🗺️ خارطة الطريق

1. **الأساس:** سجلات Windows/Linux · الشبكات · [مسار SOC](./01_SOC_Path.md)
2. **الجنائيات الأساسية:** [مسار التحليل الجنائي](./06_Digital_Forensics_Path.md)
3. **أدوات الاستجابة:** Velociraptor · KAPE · Sysinternals · Chainsaw/Hayabusa
4. **تحليل البرمجيات الخبيثة المبدئي:** Sandbox ثم Static ثم Dynamic
5. **كتابة التقارير والـ Playbooks:** نصف الشغل تواصل وتوثيق
6. **تمارين Tabletop:** تدرب على قيادة اجتماع أزمة

---

## 🎓 الشهادات

| المستوى | الشهادة | ملاحظات |
|---|---|---|
| مدخل | [CompTIA Security+](https://www.comptia.org/certifications/security) 💲 | أساس عام |
| مدخل | [Blue Team Level 1 (Security Blue Team)](https://securityblue.team/why-btl1/) 💲 | عملية وبسعر معقول |
| متوسط | [CompTIA CySA+](https://www.comptia.org/certifications/cybersecurity-analyst) 💲 | تحليل وكشف واستجابة |
| متوسط | [eCIR (INE)](https://ine.com/learning/certifications/internal/elearnsecurity-certified-incident-responder) 💲 | استجابة للحوادث عملية |
| متقدم | [GIAC GCIH](https://www.giac.org/certifications/certified-incident-handler-gcih/) 💲 | الأشهر للمتعاملين مع الحوادث |
| متقدم | [GIAC GCIA](https://www.giac.org/certifications/certified-intrusion-analyst-gcia/) 💲 | تحليل الشبكة والتسلل |
| متقدم | [GIAC GCFA](https://www.giac.org/certifications/certified-forensic-analyst-gcfa/) 💲 | تحقيق جنائي متقدم |

> ملاحظة: شهادات GIAC و SANS غالية جدًا، وغالبًا تُدفع عن طريق جهة العمل. ابدأ بالأرخص، وخل الشركة تدفع للأغلى.

---

## 🧪 تدريب عملي

| المنصة | الفائدة |
|---|---|
| [CyberDefenders](https://cyberdefenders.org) 🆓 | تحديات DFIR بملفات حقيقية |
| [Blue Team Labs Online](https://blueteamlabs.online) 🆓 | سيناريوهات حوادث كاملة |
| [LetsDefend](https://letsdefend.io) 🆓 | محاكاة عمل محلل الاستجابة |
| [TryHackMe](https://tryhackme.com) 🆓 | غرف DFIR و Windows forensics |
| [Malware-Traffic-Analysis](https://www.malware-traffic-analysis.net) 🆓 | تمارين تحليل حركة شبكة |
| [The DFIR Report](https://thedfirreport.com) 🆓 | تقارير حوادث حقيقية: اقرأها وأعد بناء التحقيق |

---

## 🛠️ الأدوات

| الفئة | الأدوات |
|---|---|
| جمع وتحقيق على النقاط الطرفية | [Velociraptor](https://docs.velociraptor.app) · [KAPE](https://www.kroll.com/en/services/cyber-risk/incident-response-litigation-support/kroll-artifact-parser-extractor-kape) · [Sysinternals](https://learn.microsoft.com/sysinternals) |
| سجلات Windows | [Chainsaw](https://github.com/WithSecureLabs/chainsaw) · [Hayabusa](https://github.com/Yamato-Security/hayabusa) · [Sigma](https://github.com/SigmaHQ/sigma) |
| الذاكرة | [Volatility 3](https://github.com/volatilityfoundation/volatility3) |
| الخط الزمني | [Plaso](https://github.com/log2timeline/plaso) · [Timesketch](https://timesketch.org) |
| الشبكة | [Wireshark](https://www.wireshark.org) · [Zeek](https://zeek.org) |
| إدارة الحادثة | [TheHive](https://github.com/TheHive-Project/TheHive) · [MISP](https://www.misp-project.org) |
| تحليل العينات | [ANY.RUN](https://any.run) · [Hybrid Analysis](https://www.hybrid-analysis.com) · [CyberChef](https://gchq.github.io/CyberChef) |

---

## 🔍 مهارات لازم تتقنها

- **التعامل مع الأزمة:** هدوء، ترتيب أولويات، تواصل واضح مع الإدارة
- **تحليل السجلات** والخطوط الزمنية
- **الاحتواء الآمن** بدون إتلاف الأدلة
- **كتابة تقرير الحادثة** (ملخص تنفيذي + تفاصيل تقنية + توصيات)
- **معرفة متطلبات التبليغ** عن الحوادث للجهات التنظيمية المعنية بقطاعك

## 📚 مصادر

[DFIR.training](https://www.dfir.training) · [SANS Reading Room](https://www.sans.org/white-papers/) · [MITRE ATT&CK](https://attack.mitre.org) · [13Cubed (يوتيوب)](https://www.youtube.com/@13Cubed)

---

⬅️ [الرئيسية](../README.md) · 🏢 [أي بيئة عمل تناسب هذا المسار؟](../guides/Work_Environments_Guide.md)
