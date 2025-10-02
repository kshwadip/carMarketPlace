# 🚗 Car Marketplace

🕛 **Live Deployment**  
https://fwebsite.onrender.com

---

## 📦 Project Overview
Car Marketplace is a modern Flutter-based **web and mobile application** that allows users to buy, sell, and browse cars.  

The project demonstrates **full-stack capabilities** with:  
- Flutter for frontend UI (web + mobile)  
- Supabase for backend (DB, auth, storage, real-time)  
- Media uploads, geolocation, and maps  

This was built as a **hands-on learning + portfolio project**, focused on implementing production-grade app architecture.

---

## 🚀 Tech Stack

**Frontend**: Flutter (Material Design, Web + Mobile)  
**Backend**: Supabase (Database, Auth, Storage, Realtime)  
**Media**: `image_picker`, `file_picker`, `video_player`  
**Maps & Location**: `google_maps_flutter`, `geolocator`  
**Routing**: `go_router`  
**State Management**: `provider`  
**Localization**: `intl`, `flutter_localizations`  
**Deployment**: Flutter Web → Render  
**Logging**: `logger`  
**Version Control**: Git / GitHub  

---

## 🛠 Dependencies & Packages

- `supabase_flutter` — realtime DB, auth, storage  
- `image_picker`, `file_picker`, `video_player` — media upload & playback  
- `path_provider` — platform file paths  
- `uuid` — unique IDs for listings  
- `collection` — advanced Dart utilities  
- `url_launcher` — external links  
- `cupertino_icons` — iOS icons  

**Dev & Build Tools**  
- `flutter_lints` — linting & static analysis  
- `flutter_test` — unit testing  
- CI/CD: Manual or GitHub-integrated (auto-deploy pending)  

---

## 🎨 UI/UX Notes
- Functionality prioritized over polish  
- Clean and usable, but not styled with design systems or animations  
- Lightweight build, no external UI frameworks  

**Implemented Core Features**  
- Media uploads (images/videos)  
- Real-time listing updates  
- Geolocation & Google Maps integration  
- Authentication & session management  

---

## 🔐 Authentication
- Powered by **Supabase Auth**  
- Email/password login  
- Session persistence  
- User-specific secure storage  

**Planned:**  
- OAuth (Google, GitHub)  
- Admin dashboard  
- Listing moderation  
- Multi-device session management  

---

## ⚙️ Deployment & CI/CD
- Deployed on **Render** (free tier)  
- Flutter Web build  
- Manual deployments currently  
- Goal: **GitHub Actions → Auto deploy on commit**  

---

## ✅ Error Handling & Logging
- Structured logging via `logger`  
- Try/catch on API calls, uploads  
- Form validation  
- Ready for small-scale use  
- Future: Sentry or Firebase Crashlytics  

---

## 📁 Future Improvements
- Search & filters for listings  
- OAuth authentication  
- Better UI/UX (Material 3, animations)  
- Admin dashboard for approval  
- Pagination / infinite scroll  
- Offline caching (Hive or local DB)  
- Payments (Stripe, Razorpay)  

---

## 🧑‍💻 About the Developer
Independently built post-B.Tech as part of a **personal portfolio**.  
Demonstrates:  
- Full-stack development (Flutter + Supabase)  
- Real-time apps with authentication & media handling  
- Deploying production-ready apps with limited infra  

---
