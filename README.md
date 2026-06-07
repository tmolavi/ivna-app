# Ivna News Mobile App (ایونا نیوز) - Landing Page

Welcome to the landing page of the **Ivna News** mobile application! 

> 🔒 **Codebase Visibility Note**
> The source code of this application is maintained in a **private repository** for proprietary, security, and commercial compliance reasons. This repository serves as a public information desk, documentation center, and feedback tracker for users, testers, and reviewers.

---

## 📝 About the Application

**Ivna News (ایونا نیوز)** is a modern, cross-platform mobile application designed as an offline-first, high-performance RSS news reader. The app provides swift, smooth, and reliable access to news feeds from the official Iranian news channels. It is fully licensed under the Ministry of Culture and Islamic Guidance.

### Key Highlights:
* **Offline Reading:** Instantly caches feed items into a local SQLite database, allowing users to browse news headlines and content even when offline.
* **Smart News Syncing:** Multi-domain fallback system that automatically parses, cleans, and merges RSS feeds from primary and fallback web endpoints.
* **Background Tasks:** Synchronizes news stories in the background to ensure users always open the app to fresh content.
* **Local Notifications:** Warns users of breaking news through customized local notifications.
* **Persian Typography:** Specially tailored user interface using the `Vazirmatn` font family and standard navy/red thematic styles.

---

## 🛠️ Technology Stack & Dependencies

The application is built on top of modern mobile technologies to guarantee performance and responsiveness:

* **Framework:** Google Flutter SDK (Dart)
* **Local Storage & Cache:** SQLite (`sqflite`), `shared_preferences`
* **Network & Services:** `http` client, `xml` parser, `connectivity_plus`
* **Native Bridges:** `url_launcher` (external calling/browsing), `share_plus` (native sharing)
* **Background Worker:** `workmanager` for scheduled background synchronizations
* **Alert System:** `flutter_local_notifications`

---

## 📥 How to Download & Test

We are excited for you to try out the app and give us your valuable feedback! You can download and install the app using the following links:

### 🇮🇷 Download from Cafe Bazaar:
👉 **[Ivna News on Cafe Bazaar](https://cafebazaar.ir/app/com.ivnanews.ivna_news_app)**

### 🤖 Download from Google Play Store:
* **Status:** *Currently under review.* The direct Google Play link will be updated here as soon as the pending publication is approved.

---

## 💬 Feedback & Bug Reports

We highly appreciate your reviews, feedback, and bug reports! 
* If you have downloaded the app and found an issue, or if you want to request a feature, please feel free to **[Open a GitHub Issue](https://github.com/tmolavi/ivna-app/issues)** on this repository.
* You can also leave your comments and ratings directly on our **Cafe Bazaar** listing page.

---

## 🔗 Official Websites & Credits

This mobile ecosystem is officially connected to and powered by:
* **Official Website:** [negaheiraniannews.ir](https://negaheiraniannews.ir)
* **Alternative Domain:** [ivnanews.com](https://ivnanews.com)
* **License Holder & Editor-in-Chief:** Dr. Mehdi Karimi Tafarshi (دکتر مهدی کریمی تفرشی)
* **Publisher:** Negahe Iranian News Agency (پایگاه خبری نگاه ایرانیان نیوز - ایونا)
