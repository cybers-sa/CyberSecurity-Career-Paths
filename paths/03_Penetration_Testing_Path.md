# 🧑‍💻 اختبار الاختراق (Penetration Testing)

> **الفكرة باختصار:** تفكر مثل المهاجم، بإذن رسمي، عشان تلقى الثغرات قبل الأشرار وتكتب تقريرًا يخلي الجهة تصلحها.

**الصعوبة:** ⭐⭐⭐⭐ · **مناسب لمن:** يحب التجربة والفضول وحل الألغاز، ويقدر يصبر على الفشل المتكرر

> ⚖️ **تنبيه قانوني مهم:** لا تختبر إلا أنظمة تملكها أو معك إذن كتابي صريح لاختبارها. الوصول غير المصرح به جريمة يعاقب عليها نظام مكافحة الجرائم المعلوماتية. تدرّب في المختبرات أدناه أو في برامج Bug Bounty الرسمية.

---

## 👤 الأدوار الوظيفية

| الدور | وش يسوي |
|---|---|
| Penetration Tester | اختبار الشبكات والتطبيقات والأنظمة وكتابة التقرير |
| Web / Mobile Application Security | تخصص في تطبيقات الويب أو الجوال |
| Red Team Operator | محاكاة خصم متقدم على مدى أسابيع |
| Bug Bounty Hunter | البحث عن ثغرات في برامج مكافآت الثغرات |
| Vulnerability / Exploit Researcher | بحث عميق في الثغرات والهندسة العكسية |

---

## 🗺️ خارطة الطريق

1. **الأساسيات (إجباري):** الشبكات · Linux بمستوى جيد · Python أو Bash · كيف يشتغل الويب (HTTP, Cookies, Sessions). [الأساسيات المشتركة](../guides/00_Foundations.md)
2. **ثغرات الويب:** OWASP Top 10 عبر [PortSwigger Academy](https://portswigger.net/web-security)
3. **اختبار الشبكات والأنظمة:** مسارات TryHackMe ثم HTB Starting Point
4. **Active Directory:** تقريبًا كل اختبار داخلي مؤسسي فيه AD، فلازم تتقنه
5. **شهادة عملية:** eJPT ← PNPT ← OSCP
6. **تخصص:** ويب متقدم · AD / Red Team · سحابة ([الأمن السحابي](./09_Cloud_Security_Path.md)) · موبايل · بحث ثغرات

---

## 🎓 الشهادات

| المستوى | الشهادة | ملاحظات |
|---|---|---|
| مبتدئ | [eJPT (INE)](https://ine.com/learning/certifications/external/elearnsecurity-junior-penetration-tester-cert) 💲 | عملية وبسيطة. ⚠️ الرابط القديم elearnsecurity.com تغيّر، المنتج الآن تحت INE |
| مبتدئ | [CompTIA PenTest+](https://www.comptia.org/certifications/penetration-tester) 💲 | نظرية وعملية، مقبولة في وظائف كثيرة |
| متوسط | [PNPT (TCM Security)](https://certifications.tcm-sec.com/pnpt/) 💲 | تختبر سلسلة اختبار اختراق كاملة مع AD وتقرير |
| متوسط | [BSCP (PortSwigger)](https://portswigger.net/web-security/certification) 💲 | الأفضل لأمن الويب، والتدريب نفسه مجاني |
| متوسط | [CEH (EC-Council)](https://www.eccouncil.org/train-certify/certified-ethical-hacker-ceh/) 💲 | معروفة وتطلبها بعض الجهات، لكنها أقل قيمة تقنية من العملية |
| متقدم | [OSCP+ (PEN-200)](https://www.offsec.com/courses/pen-200/) 💲🎓 | المعيار الذهبي العملي. OffSec عندها خصم 10% للطلاب بتوثيق |
| متقدم | [CRTP (Altered Security)](https://www.alteredsecurity.com/adlab) 💲 | متخصصة في Active Directory |

> 💡 أهم من الشهادة: **ملفك العملي.** اكتب writeups لكل مختبر تحله وانشرها في GitHub أو مدونة.

---

## 🧪 تدريب عملي

| المنصة | الفائدة |
|---|---|
| [PortSwigger Web Security Academy](https://portswigger.net/web-security) 🆓 | الأفضل لأمن الويب، مجاني بالكامل |
| [TryHackMe](https://tryhackme.com) 🆓🎓 | مسارات منظمة للمبتدئين، وبعض الغرف مجانية |
| [Hack The Box](https://www.hackthebox.com) 🆓🎓 | Starting Point و Academy، وفيه اشتراك طلاب مخفض |
| [OverTheWire](https://overthewire.org/wargames/) 🆓 | ألعاب Bandit وغيرها لتقوية Linux |
| [VulnHub](https://www.vulnhub.com) 🆓 | أجهزة افتراضية ضعيفة تنزلها وتشغلها عندك |
| [OWASP Juice Shop](https://owasp-juice.shop) 🆓 | تطبيق ويب ضعيف بشكل مقصود |
| [DVWA](https://github.com/digininja/DVWA) 🆓 | بيئة بسيطة لتجربة أساسيات ثغرات الويب |
| [PentesterLab](https://pentesterlab.com) 🆓/💲 | دروس مرتبة، وفيه محتوى مجاني |
| [Proving Grounds (OffSec)](https://www.offsec.com/labs/) 💲 | تحضير مباشر لـ OSCP |

---

## 🛠️ الأدوات

| الفئة | الأدوات |
|---|---|
| بيئة العمل | [Kali Linux](https://www.kali.org) · [Parrot OS](https://parrotsec.org) |
| استطلاع وفحص | [Nmap](https://nmap.org) · [Gobuster](https://github.com/OJ/gobuster) · [ffuf](https://github.com/ffuf/ffuf) · [Amass](https://github.com/owasp-amass/amass) |
| الويب | [Burp Suite Community](https://portswigger.net/burp/communitydownload) · [OWASP ZAP](https://www.zaproxy.org) · [sqlmap](https://sqlmap.org) |
| الاستغلال | [Metasploit](https://www.metasploit.com) · [Impacket](https://github.com/fortra/impacket) · [NetExec](https://github.com/Pennyw0rth/NetExec) |
| Active Directory | [BloodHound CE](https://github.com/SpecterOps/BloodHound) · [Responder](https://github.com/lgandx/Responder) |
| كلمات المرور | [Hashcat](https://hashcat.net) · [John the Ripper](https://www.openwall.com/john/) · [Hydra](https://github.com/vanhauser-thc/thc-hydra) |
| هندسة عكسية | [Ghidra](https://ghidra-sre.org) |
| Red Team C2 | [Sliver](https://github.com/BishopFox/sliver) · [Havoc](https://github.com/HavocFramework/Havoc) |

---

## 📚 مراجع لا تستغني عنها

- [HackTricks](https://book.hacktricks.wiki): مرجع ضخم لكل تقنية.
- [GTFOBins](https://gtfobins.github.io): رفع الصلاحيات في لينكس
- [LOLBAS](https://lolbas-project.github.io): نفس الفكرة لويندوز
- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings): حمولات وتقنيات جاهزة
- [MITRE ATT&CK](https://attack.mitre.org): فهم تقنيات المهاجم
- [OSCP Preparation Guide (HTB)](https://www.hackthebox.com/blog/oscp-preparation-guide)

## 💰 Bug Bounty (للتطبيق الحقيقي القانوني)

[HackerOne](https://www.hackerone.com) · [Bugcrowd](https://www.bugcrowd.com) · [Intigriti](https://www.intigriti.com) · ومنصة مكافآت الثغرات عبر [safcsp.org.sa](https://www.safcsp.org.sa)

---

⬅️ [الرئيسية](../README.md) · 🏢 [أي بيئة عمل تناسب هذا المسار؟](../guides/Work_Environments_Guide.md)
