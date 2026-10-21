<div dir="rtl">

# 🔍 التحليل الجنائي الرقمي (Digital Forensics)

> **الفكرة باختصار:** تجمع الأدلة الرقمية بطريقة سليمة وتحللها وتعيد بناء ما حصل، سواء لحادثة أمنية أو قضية قانونية.

**الصعوبة:** ⭐⭐⭐⭐ · **مناسب لمن:** دقيق وصبور ويحب التفاصيل والتوثيق

> ⚖️ **قاعدة ذهبية:** لا تفحص جهازًا أو بيانات إلا بتفويض رسمي، ووثّق **سلسلة الحيازة (Chain of Custody)** من أول لحظة. أي خلل فيها قد يلغي قيمة الدليل.

---

## 👤 الأدوار الوظيفية

| الدور | وش يسوي |
|---|---|
| Digital Forensics Examiner | فحص الأقراص والأجهزة واستخراج الأدلة |
| DFIR Analyst | الدمج بين الجنائيات والاستجابة للحوادث |
| Mobile Forensics Specialist | الهواتف والتطبيقات |
| Memory / Malware Forensics | تحليل الذاكرة والعينات |
| E-Discovery / Forensic Consultant | دعم القضايا والتحقيقات الداخلية |

---

## 🗺️ خارطة الطريق

1. **الأساس:** أنظمة الملفات (NTFS, FAT, ext4) · Windows internals · Linux · شبكات
2. **الإجراءات:** التصوير الجنائي (Imaging) · الحماية من الكتابة (Write Blocker) · الـ Hash · سلسلة الحيازة
3. **آثار Windows:** Registry · Prefetch · Event Logs · Shellbags · Amcache · LNK
4. **الذاكرة:** تحليل RAM باستخدام Volatility
5. **الخط الزمني:** دمج الأدلة بخط واحد
6. **التخصص:** جنائيات الجوال · السحابة · الشبكة · البرمجيات الخبيثة

---

## 🎓 الشهادات

| المستوى | الشهادة | ملاحظات |
|---|---|---|
| مدخل | [CompTIA Security+](https://www.comptia.org/certifications/security) 💲 | أساس عام |
| مدخل | [CompTIA CySA+](https://www.comptia.org/certifications/cybersecurity-analyst) 💲 | تحليل وسجلات |
| متوسط | [CHFI (EC-Council)](https://www.eccouncil.org/train-certify/computer-hacking-forensic-investigator-chfi/) 💲 | معروفة، لكن الأقوى عمليًا غيرها |
| متوسط | [GIAC GCFE](https://www.giac.org/certifications/certified-forensic-examiner-gcfe/) 💲 | جنائيات Windows الأساسية |
| متقدم | [GIAC GCFA](https://www.giac.org/certifications/certified-forensic-analyst-gcfa/) 💲 | تحقيق متقدم وكشف الاختراق |
| دورة | [SANS FOR500 / FOR508](https://www.sans.org/cyber-security-courses/windows-forensic-analysis/) 💲 | مرجع احترافي للتدريب |

---

## 🧪 تدريب عملي

| المنصة | الفائدة |
|---|---|
| [CyberDefenders](https://cyberdefenders.org) 🆓 | تحديات صور أقراص وذاكرة وسجلات |
| [Blue Team Labs Online](https://blueteamlabs.online) 🆓 | تحقيقات جنائية |
| [TryHackMe](https://tryhackme.com) 🆓 | غرف Windows Forensics وتحليل الذاكرة |
| [Magnet CTF](https://www.magnetforensics.com/blog/tag/ctf/) 🆓 | تحديات سنوية مجانية من Magnet Forensics |
| [NIST CFReDS](https://cfreds.nist.gov) 🆓 | صور جنائية مرجعية للتمرين |
| [Digital Corpora](https://digitalcorpora.org) 🆓 | مجموعات بيانات جنائية للبحث والتدريب |
| [DFIR.training](https://www.dfir.training) 🆓 | فهرس ضخم للأدوات والتمارين |

---

## 🛠️ الأدوات

| الفئة | الأدوات |
|---|---|
| منصات تحليل | [Autopsy / Sleuth Kit](https://www.autopsy.com) · [Magnet AXIOM](https://www.magnetforensics.com) 💲 (نسخة تجريبية) |
| التصوير | FTK Imager (من Exterro) · [Arsenal Image Mounter](https://arsenalrecon.com) |
| الذاكرة | [Volatility 3](https://github.com/volatilityfoundation/volatility3) · [Volatility Workbench](https://www.osforensics.com/tools/volatility-workbench.html) |
| Windows artifacts | [Eric Zimmerman's Tools](https://ericzimmerman.github.io) · [KAPE](https://www.kroll.com/en/services/cyber-risk/incident-response-litigation-support/kroll-artifact-parser-extractor-kape) |
| الخط الزمني | [Plaso / log2timeline](https://github.com/log2timeline/plaso) · [Timesketch](https://timesketch.org) |
| بيئة جاهزة | [SIFT Workstation](https://www.sans.org/tools/sift-workstation/) |

---

## 📚 مصادر

[This Week in 4n6](https://thisweekin4n6.com) · [13Cubed (يوتيوب)](https://www.youtube.com/@13Cubed) · [SANS Reading Room](https://www.sans.org/white-papers/) · [Malware-Traffic-Analysis](https://www.malware-traffic-analysis.net)

---

⬅️ [الرئيسية](../README.md) · 🏢 [أي بيئة عمل تناسب هذا المسار؟](../guides/Work_Environments_Guide.md)

</div>
