# EzBill · ايصالك

**A secure digital vault for receipts and bills.**
خزنتك الرقمية الآمنة: احفظ كل فواتيرك في السحابة مع الحماية بالبصمة.

> Built for a client · ~200 daily active users · Source code is private

<p align="center">
<img src="screenshots/flutter_01.png" width="240">
<img src="screenshots/flutter_02.png" width="240">
<img src="screenshots/flutter_03.png" width="240">
</p>

## ✨ Features
- 📸 Scan receipts and extract text automatically (OCR)
- 🔐 Biometric login (Face ID / fingerprint)
- 🔔 Due-date reminders and push notifications (Firebase + Huawei Push)
- ☁️ Cloud sync and secure storage
- 📤 Easy sharing of receipts
- 🌐 Arabic & English
- 🖥️ Admin dashboard: users, receipts, reports and support tickets

## 🛠️ Tech stack
| Part | Tech |
|---|---|
| Mobile app | Flutter · Dart · Riverpod · GoRouter |
| Backend & DB | Supabase (PostgreSQL, Auth, Storage) |
| Notifications | Firebase Cloud Messaging · Huawei Push |
| OCR | Google ML Kit |
| Admin panel | Next.js · TypeScript · Tailwind · React Query |
