<div dir="rtl">

# 🔐 إدارة الهوية والوصول (IAM)

> **الفكرة باختصار:** تتأكد أن الشخص الصح يوصل للشيء الصح في الوقت الصح، وبالصلاحية الأقل المطلوبة. أغلب الاختراقات الحديثة تبدأ من هوية مسروقة، فهذا المسار حساس جدًا.

**الصعوبة:** ⭐⭐⭐ · **مناسب لمن:** يحب الأنظمة المؤسسية والتكامل بين التطبيقات

---

## 👤 الأدوار الوظيفية

| الدور | وش يسوي |
|---|---|
| IAM Analyst / Administrator | إدارة الحسابات والصلاحيات ودورة حياة المستخدم |
| IAM Engineer | بناء SSO و MFA وتكاملات الهوية |
| PAM Engineer | حماية الحسابات المميزة (الأدمن) |
| Identity Architect | تصميم منظومة الهوية للمؤسسة |
| Directory / AD Security | تأمين Active Directory و Entra ID |

---

## 🗺️ خارطة الطريق

1. **المفاهيم:** المصادقة مقابل التفويض · RBAC / ABAC · Least Privilege · دورة حياة الهوية (Joiner-Mover-Leaver)
2. **الأدلة والبروتوكولات:** LDAP · Kerberos · SAML · OAuth 2.0 · OpenID Connect · FIDO2 / Passkeys
3. **Active Directory و Entra ID:** أساس أغلب بيئات المؤسسات
4. **MFA و SSO و Conditional Access**
5. **PAM:** إدارة الصلاحيات المميزة وJust-in-Time
6. **IGA:** مراجعة الصلاحيات الدورية (Access Reviews)
7. **الأمن:** هجمات AD (Kerberoasting, Pass-the-Hash) والدفاع منها

---

## 🎓 الشهادات

| المستوى | الشهادة | ملاحظات |
|---|---|---|
| مدخل | [Microsoft SC-900](https://learn.microsoft.com/en-us/credentials/certifications/security-compliance-and-identity-fundamentals/) 💲 | أساسيات الأمن والهوية في Microsoft |
| مدخل | [CompTIA Security+](https://www.comptia.org/certifications/security) 💲 | مفاهيم التحكم بالوصول والمصادقة |
| متوسط | [Microsoft SC-300](https://learn.microsoft.com/en-us/credentials/certifications/identity-and-access-administrator/) 💲 | ⚠️ ستتحدث نسخته الإنجليزية في **28 أكتوبر 2026**، راجع دليل الدراسة قبل الحجز |
| متوسط | [Okta Certified Professional](https://www.okta.com/education/) 💲 | إذا كانت بيئتك Okta |
| تخصص | [CyberArk Defender](https://www.cyberark.com/services-support/cyberark-university/) 💲 | للـ PAM |
| سحابة | [AWS Certified Security – Specialty (SCS-C03)](https://aws.amazon.com/certification/certified-security-specialty/) 💲 | IAM بعمق في AWS |
| متقدم | [CISSP](https://www.isc2.org/certifications/cissp) 💲 | دومين كامل للهوية والوصول |

---

## 🧪 تدريب عملي

| المنصة | الفائدة |
|---|---|
| [Microsoft Learn: SC-300 Learning Path](https://learn.microsoft.com/en-us/training/paths/sc-300-implement-an-identity-management-solution/) 🆓 | تعلم Entra ID عمليًا مع مختبرات |
| [Entra ID Free](https://www.microsoft.com/security/business/microsoft-entra-pricing) 🆓 | نسخة مجانية تجرب فيها بيئة حقيقية |
| [AWS Workshops](https://workshops.aws) 🆓 | ورش IAM عملية |
| [Auth0 Learn](https://auth0.com/learn) 🆓 | شرح OIDC و OAuth2 و SSO |
| [Keycloak](https://www.keycloak.org) 🆓 | نظام هوية مفتوح، ركّبه وجرّب SSO بنفسك |
| [TryHackMe](https://tryhackme.com) 🆓 | غرف عن Active Directory و Kerberos |
| [Hack The Box Academy](https://academy.hackthebox.com) 🆓/🎓 | وحدات AD |

---

## 🛠️ الأدوات والتقنيات

| الفئة | أدوات |
|---|---|
| الأدلة | Active Directory · [Microsoft Entra ID](https://www.microsoft.com/security/business/identity-access/microsoft-entra-id) · [FreeIPA](https://www.freeipa.org) · OpenLDAP |
| SSO / IdP مفتوح | [Keycloak](https://www.keycloak.org) · [authentik](https://goauthentik.io) |
| PAM | CyberArk · Delinea · [HashiCorp Vault](https://www.vaultproject.io) |
| تدقيق AD | [PingCastle](https://www.pingcastle.com) · [BloodHound CE](https://github.com/SpecterOps/BloodHound) |
| سحابة | AWS IAM · Azure RBAC · GCP IAM |

---

## 🔍 مهارات لازم تتقنها

- تصميم نموذج صلاحيات (RBAC) سليم وتجنب "تضخم الصلاحيات"
- ضبط SSO و MFA وربطها بالتطبيقات
- قراءة وتحليل سجلات تسجيل الدخول وكشف الشذوذ
- فهم هجمات الهوية والدفاع منها
- معرفة متطلبات الهوية والوصول في [ضوابط ECC](https://nca.gov.sa/en/regulatory-documents/controls-list/ecc/)

---

⬅️ [الرئيسية](../README.md) · 🏢 [أي بيئة عمل تناسب هذا المسار؟](../guides/Work_Environments_Guide.md)

</div>
