# Integrated-Social-Media-Groups-App
Android application that aggregates social media groups into a single platform using a custom-built API. Features include group browsing, posting, and real-time notifications.
# 🌐 Integrated Social Media Groups App

## 📱 Overview
**Integrated Social Media Groups App** is a complete mobile-based system designed to simplify access to various social media groups across multiple platforms.  
The project includes two Android applications — one for users and one for administrators — both powered by a secure Laravel-based backend API.

Users can easily discover, search, and filter groups by platform, category, and language, while administrators manage and moderate all content directly from a dedicated Android Admin App.

---

## 🚀 Key Features
### 👥 User App
- 🔍 **Smart Filtering System** — Search groups by:
  - Platform (WhatsApp, Telegram, Facebook, etc.)
  - Category (Education, Business, Technology, etc.)
  - Language (English, Arabic, etc.)
- ⚡ **Multi-Platform Support** — Access different platforms from one place.
- 🌍 **Dynamic Search** — Find groups quickly using keywords.
- 💬 **Direct Group Links** — Join groups instantly via integrated links.
- ✨ **Modern UI** — Clean, fast, and responsive design.
- 🧩 **Submit New Groups** — Users can add their own groups pending admin approval.

---

### 🖥️ Admin App
The **Admin Dashboard** is a separate **Android application built in Java**, connected to the same Laravel API.  
It provides complete control over the app’s data and user-submitted content.

#### 🛠️ Admin Features:
- 🔐 **Secure Login System** for admin access.
- ➕ **Add New Applications** (e.g., WhatsApp, Telegram, etc.).
- 🗂️ **Manage Categories** — Create, update, or delete categories.
- 👥 **Manage Groups** — View, approve, or reject groups submitted by users.
- ✏️ **Edit or Delete Groups** at any time.
- 📨 **Pending Approval System** — Review and approve new groups before they appear publicly.
- 📊 **Overview Dashboard** — Displays statistics about apps, categories, and groups.

Both applications communicate with the backend API to ensure real-time synchronization between user submissions and admin approvals.

---

## 🛠️ Technologies Used
| Component | Technology |
|------------|-------------|
| **User App** | Java (Android SDK) |
| **Admin App** | Java (Android SDK) |
| **Backend API** | Laravel (PHP Framework) |
| **Database** | MySQL |
| **Architecture** | RESTful API |
| **Version Control** | Git & GitHub |
| **Testing Tools** | Postman, Android Studio |

---

## 🧩 System Workflow
1. The **Laravel backend** serves as the main API provider.
2. Users browse and filter groups via the **User App**.
3. When a user submits a new group, it is stored as **“pending approval.”**
4. The **Admin App** retrieves pending groups for review.
5. Admins can **approve or reject** submissions.
6. Approved groups immediately become visible to all users.

---

## 🎯 Purpose
The main goal of this system is to provide a unified mobile experience for exploring, managing, and moderating social media groups — all within a structured, admin-controlled environment.

---

## 👨‍💻 My Role
I was responsible for the **entire development process**, including:
- Building the **Laravel backend API**.
- Developing the **User Android App** using Java.
- Creating the **Admin Android App** for management and moderation.
- Designing UI/UX for both applications.
- Implementing secure communication between apps and backend.
- Testing, debugging, and deployment.

---

## 🧠 Challenges & Solutions
| Challenge | Solution |
|------------|-----------|
| Managing multiple platforms dynamically | Created scalable platform configuration system. |
| Handling user submissions securely | Implemented token-based authentication and approval workflow. |
| Synchronizing user and admin apps | Used RESTful API with status updates for real-time sync. |
| Ensuring smooth UX on mobile | Optimized layouts and network requests with caching. |

---

## 📸 Screenshots
*(Add your screenshots in `/screenshots` folder)*

| User App | Admin App | Backend Overview |
|-----------|------------|------------------|
| ![User](screenshots/user.png) | ![Admin](screenshots/admin.png) | ![Backend](screenshots/backend.png) |

---

## 📲 Download the App

You can try the applications directly from the Google Play Store:

### 🧭 User App
📱 **Social Media Groups App**  
🔗 [Download from Google Play]([https://play.google.com/store/apps/details?id=com.yourcompany.userapp](https://play.google.com/store/apps/details?id=com.akgroupslinks))


