# MVP Features Map – Event Management Platform (Syria)

## MVP Scope Summary
This MVP focuses on core discovery and viewing of events with basic user accounts.

### Included Features (MVP)
- User Registration & Login (Email only)
- Browse Events List
- Event Details Page
- External Registration Link
- Static Policy Pages (Privacy, Terms)
- Full Arabic Language Support
- Mobile-first, Low-bandwidth Optimized UI

### Deferred / Future Features
- Organizer Dashboard & Event Creation
- Admin Review & Moderation
- Payments & Ticketing
- Notifications
- Advanced Search & Filters

---

## Features Overview Table

| FeatureId      | FeatureName              | FeatureType | Summary                                      | Personas               | Requirements            | SpecFolders                     | Priority | Status   |
|----------------|--------------------------|-------------|----------------------------------------------|------------------------|-------------------------|----------------------------------|----------|----------|
| FEAT-EXAMPLE01 | Example Feature          | CRUD        | مثال لميزة CRUD كاملة (إنشاء/عرض/تعديل/حذف) | Admin, User            | FR-EX-01, FR-EX-02      | 04-domain, 07-api, 08-ui         | P1       | Planned  |
| FEAT-USER-AUTH | User Registration & Login| Auth        | تسجيل المستخدمين وتسجيل الدخول عبر البريد الإلكتروني فقط مع دعم اللغة العربية | Participant             | FR-AUTH-01, FR-AUTH-02  | 04-domain, 07-api, 08-ui         | P1       | Planned  |
| FEAT-EVENT-LIST| Browse Events            | Read        | استعراض قائمة الفعاليات الجارية والقادمة مع معلومات أساسية لكل فعالية | Participant             | FR-EVENT-01             | 04-domain, 07-api, 08-ui         | P1       | Planned  |
| FEAT-EVENT-DET | Event Details Page       | Read        | صفحة تفاصيل الفعالية مع الوصف والمكان والزمان ورابط تسجيل خارجي | Participant             | FR-EVENT-02             | 04-domain, 07-api, 08-ui         | P1       | Planned  |
| FEAT-POLICIES  | Static Policy Pages      | Content     | صفحات ثابتة لسياسة الخصوصية والأحكام والشروط | All Users               | FR-CONTENT-01           | 08-ui                            | P2       | Planned  |

---

## ✅ Features Table (Confirmed MVP)

| FeatureId      | FeatureName        | FeatureType | Summary                                      | Personas         | Requirements      | SpecFolders                             | Priority | Status      |
|----------------|--------------------|-------------|----------------------------------------------|------------------|-------------------|------------------------------------------|----------|------------|
| FEAT-EXAMPLE01 | Example Feature    | CRUD        | مثال لميزة CRUD كاملة (إنشاء/عرض/تعديل/حذف) | Admin, User      | FR-EX-01, FR-EX-02 | 04-domain, 07-api, 08-ui                | P1       | Planned    |
| FEAT-USER-AUTH | User Registration & Login | Auth | تسجيل المستخدمين وتسجيل الدخول عبر البريد الإلكتروني فقط | Participant | FR-AUTH-01, FR-AUTH-02 | 04-domain, 07-api, 08-ui | P1 | Planned |
| FEAT-EVENT-LIST | Browse Events | Read | استعراض الفعاليات الجارية والقادمة مع بيانات مختصرة | Participant | FR-EVENT-01 | 04-domain, 07-api, 08-ui | P1 | Planned |
| FEAT-EVENT-DET | Event Details Page | Read | عرض تفاصيل الفعالية كاملة مع رابط تسجيل خارجي | Participant | FR-EVENT-02 | 04-domain, 07-api, 08-ui | P1 | Planned |
| FEAT-POLICIES | Static Policy Pages | Content | صفحات سياسة الخصوصية والأحكام والشروط | All Users | FR-CONTENT-01 | 08-ui | P2 | Planned |
