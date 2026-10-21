<div dir="rtl">

# 🌐 أمن الشبكات (Network Security)

> **الفكرة باختصار:** تصمم وتأمّن وتراقب الشبكة اللي تمر عليها كل البيانات: جدران نارية، VPN، تقسيم الشبكة، وكشف التسلل.

**الصعوبة:** ⭐⭐⭐ · **مناسب لمن:** يحب البنية التحتية وفهم كيف تمشي الحزم من نقطة لنقطة

---

## 👤 الأدوار الوظيفية

| الدور | وش يسوي |
|---|---|
| Network Security Engineer | إعداد وإدارة الجدران النارية و VPN وتقسيم الشبكة |
| Firewall / Security Administrator | تشغيل الأجهزة الأمنية يوميًا ومراجعة القواعد |
| Network Security Architect | تصميم الشبكة الآمنة والـ Zero Trust |
| NDR / IDS Analyst | مراقبة حركة الشبكة وكشف الشذوذ |

---

## 🗺️ خارطة الطريق

1. **أساسيات الشبكات:** نموذج OSI/TCP-IP · عناوين IP والـ Subnetting · DNS و DHCP و NAT · التوجيه والتبديل · VLANs
2. **أمن الشبكات:** جدران نارية · IDS/IPS · VPN (IPsec, SSL) · TLS/PKI · Segmentation · NAC
3. **تحليل الحزم:** Wireshark وقراءة الـ PCAP
4. **التطبيق العملي:** ابن مختبرًا افتراضيًا فيه جدار ناري و IDS وشبكتين
5. **التخصص:** Zero Trust · SASE · أمن السحابة ([الأمن السحابي](./09_Cloud_Security_Path.md)) · أمن الشبكات الصناعية (OT)

---

## 🎓 الشهادات

| المستوى | الشهادة | ملاحظات |
|---|---|---|
| مدخل | [CompTIA Network+](https://www.comptia.org/certifications/network) 💲 | أساسيات الشبكات |
| مدخل | [Fortinet Certified Fundamentals](https://training.fortinet.com) 🆓/💲 | تدريب Fortinet الأساسي متاح مجانًا، وتأكد من تكلفة الاختبار |
| مدخل | [CompTIA Security+](https://www.comptia.org/certifications/security) 💲 | حلقة وصل بين الشبكات والأمن |
| متوسط | [Cisco CCNA](https://www.cisco.com/site/us/en/learning/certifications/ccna/) 💲 | المعيار الأشهر في الشبكات |
| متوسط | [Cisco CyberOps Associate](https://www.cisco.com/site/us/en/learning/certifications/cyberops-associate/) 💲 | عمليات الأمن في بيئة Cisco |
| متوسط | [PCNSA (Palo Alto)](https://www.paloaltonetworks.com/services/education/certification/pcnsa) 💲 | إدارة الجدران النارية من Palo Alto |
| متقدم | [Cisco CCNP Security](https://www.cisco.com/site/us/en/learning/certifications/security/) 💲 | تصميم وتنفيذ حلول Cisco الأمنية |
| متقدم | [CISSP](https://www.isc2.org/certifications/cissp) 💲 | الدومين الرابع يغطي أمن الشبكات |

> 💡 اختر الشهادة حسب **المنتج اللي تستخدمه الجهة اللي تستهدفها** (Cisco, Fortinet, Palo Alto, Check Point).

---

## 🧪 تدريب عملي

| المنصة | الفائدة |
|---|---|
| [Cisco Packet Tracer / NetAcad](https://www.netacad.com) 🆓 | محاكي شبكات مجاني مع دورات من Cisco |
| [GNS3](https://www.gns3.com) 🆓 | محاكاة بأنظمة حقيقية |
| [EVE-NG Community](https://www.eve-ng.net) 🆓 | محاكاة قوية لأجهزة أمنية متعددة |
| [TryHackMe](https://tryhackme.com) 🆓 | غرف عن تحليل الشبكات والجدران النارية |
| [Hack The Box](https://www.hackthebox.com) 🆓 | بيئات لاختبار ضعف الشبكات والبروتوكولات |
| [Wireshark Sample Captures](https://wiki.wireshark.org/SampleCaptures) 🆓 | ملفات PCAP جاهزة للتمرين |
| [Malware-Traffic-Analysis](https://www.malware-traffic-analysis.net) 🆓 | حركة شبكة خبيثة حقيقية للتحليل |

---

## 🛠️ الأدوات

| الفئة | الأدوات |
|---|---|
| تحليل الحزم | [Wireshark](https://www.wireshark.org) · [tcpdump](https://www.tcpdump.org) · [Zeek](https://zeek.org) |
| فحص | [Nmap](https://nmap.org) |
| جدران نارية مفتوحة | [pfSense](https://www.pfsense.org) · [OPNsense](https://opnsense.org) |
| كشف التسلل | [Suricata](https://suricata.io) · [Snort](https://www.snort.org) · [Security Onion](https://securityonionsolutions.com) |
| VPN | [WireGuard](https://www.wireguard.com) · [OpenVPN](https://openvpn.net) |

---

## 🔍 مهارات لازم تتقنها

- قراءة ملف PCAP وفهم ما يحدث فيه
- كتابة قواعد جدار ناري سليمة وتنظيف القواعد القديمة
- تقسيم الشبكة (Segmentation) وفهم Zero Trust. راجع [NIST SP 800-207](https://csrc.nist.gov/pubs/sp/800/207/final)
- ضبط TLS والشهادات الرقمية
- استكشاف أعطال الاتصال (Troubleshooting)

## 📰 مصادر متابعة

[PacketLife](https://packetlife.net) · [Cisco Security Center](https://www.cisco.com/c/en/us/about/security-center.html) · [BleepingComputer](https://www.bleepingcomputer.com)

---

⬅️ [الرئيسية](../README.md) · 🏢 [أي بيئة عمل تناسب هذا المسار؟](../guides/Work_Environments_Guide.md)

</div>
