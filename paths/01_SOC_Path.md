# 📊 مركز العمليات الأمنية (SOC)

> **الفكرة باختصار:** أنت خط الدفاع الأول. تراقب التنبيهات، تفرزها، تحقق فيها، وتصعّد الحوادث الحقيقية لفريق الاستجابة.

**الصعوبة:** ⭐⭐ (من أسهل المسارات دخولًا) · **مناسب لمن:** يحب التحليل والتحقيق ولا يمانع نظام المناوبات

---

## 👤 الأدوار الوظيفية

| الدور | وش يسوي |
|---|---|
| SOC Analyst L1 | فرز التنبيهات وتحليلها الأولي |
| SOC Analyst L2 | تحقيق أعمق، احتواء، وتصعيد |
| SOC Analyst L3 / Threat Hunter | صيد التهديدات واستباق المهاجم |
| Detection Engineer | كتابة قواعد الكشف وتحسينها (Sigma, SPL, KQL) |
| SOC Lead / Manager | إدارة الفريق والمؤشرات والتقارير |

---

## 🗺️ خارطة الطريق

**1️⃣ الأساسيات (٢–٣ أشهر):** الشبكات (TCP/IP, DNS, HTTP) · Windows و Linux · قراءة السجلات · Python أو Bash بمستوى بسيط.
راجع [الأساسيات المشتركة](../guides/00_Foundations.md).

**2️⃣ أدوات المحلل (٢–٣ أشهر):** SIEM (Splunk أو Elastic أو Wazuh) · Wireshark · أساسيات EDR · إطار [MITRE ATT&CK](https://attack.mitre.org).

**3️⃣ ممارسة حقيقية (مستمر):** حل سيناريوهات تحقيق كل أسبوع، وكتابة تقرير قصير لكل حالة. هذا اللي يبني ملفك للتوظيف.

**4️⃣ التخصص:** Detection Engineering · Threat Hunting · DFIR ([مسار الاستجابة](./05_Incident_Response_Path.md) و[التحليل الجنائي](./06_Digital_Forensics_Path.md)).

---

## 🎓 الشهادات (مرتبة حسب المستوى)

| المستوى | الشهادة | ملاحظات |
|---|---|---|
| مبتدئ | [CompTIA Security+](https://www.comptia.org/certifications/security) 💲 | أساس عام يطلبه كثير من أصحاب العمل |
| مبتدئ | [Google Cybersecurity Certificate](https://grow.google/certificates/cybersecurity/) | على منصة Coursera، تحقق من التكلفة وخيار المساعدة المالية |
| مبتدئ | [TryHackMe SOC Level 1](https://tryhackme.com) 💲🎓 | مسار عملي مع شهادة، ومناسب للمبتدئين |
| متوسط | [CompTIA CySA+](https://www.comptia.org/certifications/cybersecurity-analyst) 💲 | تحليل التهديدات والاستجابة |
| متوسط | [Microsoft SC-200](https://learn.microsoft.com/en-us/credentials/certifications/security-operations-analyst/) 💲 | Sentinel و Defender، مناسبة لو بيئتك Microsoft. ⚠️ ستتحدث نسخته الإنجليزية في 21 أكتوبر 2026 |
| متوسط | [Splunk Core Certified User / Power User](https://www.splunk.com/en_us/training/certification.html) 💲 | إذا بيئتك Splunk. 🎓 يوجد تدريب مجاني للطلاب، شوف مشروع Student-EDU-Perks |
| متقدم | [GIAC GCIH](https://www.giac.org/certifications/certified-incident-handler-gcih/) · [GCIA](https://www.giac.org/certifications/certified-intrusion-analyst-gcia/) 💲 | غالية لكنها قوية ومعتمدة عالميًا |
| إدارة | [CISM](https://www.isaca.org/credentialing/cism) 💲 | لاحقًا لو تبي تقود فريق، ما تحتاجها في بداياتك |

> 💡 **CEH** كانت في النسخة القديمة من هذا الملف. هي معروفة وتطلبها بعض الجهات، لكنها ليست الأولوية لمحلل SOC. ابدأ بالعملي، وخذها فقط إذا طلبتها الوظيفة اللي تستهدفها.

---

## 🧪 تدريب عملي (🆓 = مجاني أو فيه مستوى مجاني)

| المنصة | الفائدة |
|---|---|
| [TryHackMe](https://tryhackme.com) 🆓 | مسار SOC Level 1 و Blue Team، مناسب للبداية |
| [LetsDefend](https://letsdefend.io) 🆓 | بيئة تحاكي عمل المحلل الحقيقي: تنبيهات، تذاكر، تحقيق |
| [CyberDefenders](https://cyberdefenders.org) 🆓 | تحديات تحقيق بملفات حقيقية (PCAP, Logs, Memory) |
| [Blue Team Labs Online](https://blueteamlabs.online) 🆓 | سيناريوهات تحقيق ودفاع |
| [Splunk BOTSv3](https://github.com/splunk/botsv3) 🆓 | مجموعة بيانات ضخمة للتدرب على الصيد والتحقيق في Splunk |
| [Malware-Traffic-Analysis](https://www.malware-traffic-analysis.net) 🆓 | تمارين تحليل حركة شبكة لهجمات حقيقية |
| [Atomic Red Team](https://atomicredteam.io) 🆓 | نفّذ تقنية هجومية وشوف هل قاعدة الكشف عندك تلقطها |

---

## 🛠️ الأدوات

| الفئة | مجاني / مفتوح المصدر | تجاري (للتعرف عليه) |
|---|---|---|
| SIEM | [Wazuh](https://wazuh.com) · [Elastic Security](https://www.elastic.co/security) · [Security Onion](https://securityonionsolutions.com) | Splunk · Microsoft Sentinel · QRadar |
| EDR / نقاط النهاية | [Velociraptor](https://docs.velociraptor.app) · Wazuh | CrowdStrike · SentinelOne · Defender for Endpoint |
| إدارة الحوادث / SOAR | [TheHive](https://github.com/TheHive-Project/TheHive) · [Shuffle](https://shuffler.io) | Palo Alto XSOAR |
| استخبارات التهديدات | [MISP](https://www.misp-project.org) · [OpenCTI](https://github.com/OpenCTI-Platform/opencti) | Recorded Future |
| فحص المؤشرات (IOC) | [VirusTotal](https://www.virustotal.com) · [AbuseIPDB](https://www.abuseipdb.com) · [URLScan](https://urlscan.io) · [ANY.RUN](https://any.run) · [CyberChef](https://gchq.github.io/CyberChef) | |
| قواعد الكشف | [Sigma](https://github.com/SigmaHQ/sigma) · [MITRE ATT&CK Navigator](https://mitre-attack.github.io/attack-navigator) | |

---

## 🔍 مهارات لازم تتقنها

- قراءة سجلات Windows (Event IDs المهمة: 4624, 4625, 4688, 4720...) و Linux (auth, syslog)
- كتابة استعلامات في SIEM
- التفريق بين False Positive و True Positive
- كتابة تقرير حادثة واضح ومختصر
- فهم مراحل الهجوم (Kill Chain) وتقنيات ATT&CK
- التواصل مع الفرق الأخرى أثناء الحادثة

---

## 📰 تابع المستجدات

- [BleepingComputer](https://www.bleepingcomputer.com) · [The Hacker News](https://thehackernews.com)
- [The DFIR Report](https://thedfirreport.com): تقارير تحقيق حقيقية مفصلة خطوة بخطوة، من أفضل مصادر التعلم
- [CISA Known Exploited Vulnerabilities](https://www.cisa.gov/known-exploited-vulnerabilities-catalog): الثغرات المستغلة فعليًا
- [الهيئة الوطنية للأمن السيبراني](https://nca.gov.sa): التحذيرات والتعاميم الرسمية

---

⬅️ [الرئيسية](../README.md) · 🏢 [أي بيئة عمل تناسب هذا المسار؟](../guides/Work_Environments_Guide.md)
