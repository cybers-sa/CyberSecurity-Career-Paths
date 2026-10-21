# 🏗️ هندسة الأمن (Security Engineering)

> **الفكرة باختصار:** تبني الأمن داخل الأنظمة من البداية: تصميم بنية آمنة، تقوية الأنظمة، أتمتة الضوابط، وإدخال الأمن في دورة تطوير البرمجيات.

**الصعوبة:** ⭐⭐⭐⭐ · **مناسب لمن:** عنده خلفية تقنية (نظم، شبكات، أو برمجة) ويحب البناء والأتمتة

---

## 👤 الأدوار الوظيفية

| الدور | وش يسوي |
|---|---|
| Security Engineer | بناء وتشغيل الأدوات والضوابط الأمنية |
| Security Architect | تصميم المعمارية الأمنية للأنظمة والمؤسسة |
| DevSecOps Engineer | دمج الأمن في CI/CD |
| Application Security Engineer | أمن التطبيقات: مراجعة كود، SAST/DAST |
| Detection Engineer | بناء الكشف والتنبيهات |

---

## 🗺️ خارطة الطريق

1. **الأساس التقني:** Linux · الشبكات · برمجة (Python أو Go) · Git
2. **تقوية الأنظمة (Hardening):** CIS Benchmarks · SELinux/AppArmor · إدارة التحديثات
3. **الأتمتة والبنية ككود:** Ansible · Terraform · CI/CD
4. **أمن التطبيقات والـ DevSecOps:** OWASP Top 10 · SAST/DAST/SCA · إدارة الأسرار
5. **الحاويات و Kubernetes** ثم [الأمن السحابي](./09_Cloud_Security_Path.md)
6. **المعمارية:** Zero Trust · Defense in Depth · نمذجة التهديدات

---

## 🎓 الشهادات

| المستوى | الشهادة | ملاحظات |
|---|---|---|
| مدخل | [CompTIA Security+](https://www.comptia.org/certifications/security) 💲 | أساس عام |
| مدخل | [Google Cybersecurity Certificate](https://grow.google/certificates/cybersecurity/) | على Coursera، تحقق من التكلفة والمساعدة المالية |
| متوسط | [GIAC GSEC](https://www.giac.org/certifications/security-essentials-gsec/) 💲 | مفاهيم تقنية واسعة |
| متوسط | [CompTIA CySA+](https://www.comptia.org/certifications/cybersecurity-analyst) 💲 | تحليل وكشف |
| متوسط | [CKS (CNCF)](https://training.linuxfoundation.org/certification/certified-kubernetes-security-specialist/) 💲 | أمن Kubernetes |
| متقدم | [CISSP](https://www.isc2.org/certifications/cissp) 💲 | دومين عن المعمارية والهندسة الأمنية |
| متقدم | [CCSP](https://www.isc2.org/certifications/ccsp) 💲 | للمعمارية السحابية |

---

## 🧪 تدريب عملي

| المنصة | الفائدة |
|---|---|
| [TryHackMe](https://tryhackme.com) 🆓 | Linux hardening و logging و firewalls |
| [CyberDefenders](https://cyberdefenders.org) 🆓 | سيناريوهات الكشف والمراقبة |
| [OWASP Juice Shop](https://owasp-juice.shop) 🆓 | تدريب أمن التطبيقات |
| [Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat) 🆓 | بيئة Kubernetes ضعيفة للتدريب |
| [Open Security Training](http://opensecuritytraining.info/) 🆓 | دروس عميقة في أنظمة التشغيل والذاكرة |
| [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org) 🆓 | إرشادات مختصرة لكل موضوع في أمن التطبيقات |

---

## 🛠️ الأدوات

| الفئة | الأدوات |
|---|---|
| SIEM / مراقبة | [Wazuh](https://wazuh.com) · [Elastic](https://www.elastic.co/security) · Splunk |
| IDS/IPS وجدران | [Suricata](https://suricata.io) · [pfSense](https://www.pfsense.org) · [OPNsense](https://opnsense.org) |
| تقوية الأنظمة | [Lynis](https://cisofy.com/lynis) · [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks) · [OpenSCAP](https://www.open-scap.org) |
| البنية ككود | [Terraform](https://www.terraform.io) · [Ansible](https://www.ansible.com) |
| فحص الكود | [Semgrep](https://semgrep.dev) · [OWASP ZAP](https://www.zaproxy.org) · [Gitleaks](https://github.com/gitleaks/gitleaks) · [Trivy](https://trivy.dev) |
| فحص IaC | [Checkov](https://www.checkov.io) |
| سحابة | [Prowler](https://github.com/prowler-cloud/prowler) · [ScoutSuite](https://github.com/nccgroup/ScoutSuite) |

---

## 👷‍♂️ المهام اليومية

- تصميم بنية آمنة للشبكات والأنظمة والتطبيقات
- تطبيق السياسات الأمنية تقنيًا وتوثيقها
- إدارة الثغرات والتحديثات الأمنية
- بناء وتشغيل أدوات الكشف والصد
- العمل مع فرق DevOps لتأمين خطوط CI/CD

## 📚 مصادر

[OWASP](https://owasp.org) · [OWASP SAMM](https://owaspsamm.org) · [NIST SP 800-207 (Zero Trust)](https://csrc.nist.gov/pubs/sp/800/207/final) · [MITRE ATT&CK](https://attack.mitre.org)

---

⬅️ [الرئيسية](../README.md) · 🏢 [أي بيئة عمل تناسب هذا المسار؟](../guides/Work_Environments_Guide.md)
