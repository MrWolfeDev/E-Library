# 📚 E-Library — Native Android Book App

![Kotlin](https://img.shields.io/badge/Kotlin-1.9-blue?style=for-the-badge&logo=kotlin)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-%F0%9F%92%BC-orange?style=for-the-badge)
![Firebase](https://img.shields.io/badge/Firebase-Storage-yellow?style=for-the-badge&logo=firebase)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Platform](https://img.shields.io/badge/Android-Native-lightgreen?style=for-the-badge)

> **A modern Android book reading app** built with **Jetpack Compose**, powered by **Firebase Storage** for hosting book files, and designed with clean architecture principles.

---

## ✨ Features

- **📱 Native Android** — Built entirely with **Jetpack Compose**
- **📂 Firebase Storage** — Securely store and retrieve book data
- **⚡ Fast & Modern UI** — Smooth, responsive design
- **🛠️ Dependency Injection** — Using **Hilt**
- **🧭 Navigation** — Powered by **Compose Navigation**
- **📚 Book Categories** — Browse books by category
- **📖 Book Viewer** — View complete book content directly in the app

---

## 📡 Business Logic (How the App Works)

The app’s “brain” follows three main rules for getting information:

1. **Get All Books** — Brings back a list of every book in the library.
2. **Get All Categories** — Finds all the different categories or genres (like Fiction, History, Science, etc.).
3. **Get Books by Category** — Shows only the books from one specific category you choose.

In simple words:  
- First, it can get *everything*.  
- Second, it can get *just the category names*.  
- Third, it can get *only the books that match the category you picked*.

---
| Layer        | Technology                |
| ------------ | ------------------------- |
| UI           | Jetpack Compose           |
| Navigation   | Compose Navigation        |
| Data Storage | Firebase Storage          |
| DI Framework | Hilt                      |
| Language     | Kotlin                    |
| Architecture | MVVM + Clean Architecture |

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/n-aryanshi/E-Library.git
cd E-Library
```

---
### 2️⃣ Open in Android Studio

- 📦 Install the latest **Android Studio Giraffe+**
- 🔧 Sync Gradle

### 3️⃣ Setup Firebase

1. Go to [Firebase Console](https://console.firebase.google.com/)  
2. Create a project and enable **Firebase Storage**  
3. Download `google-services.json` and place it in the `app/` folder  
4. Adjust Firebase rules if needed for public access/testing

---

## 📷 Screenshots

<table>
  <tr>
    <th>🏠 Home</th>
    <th>📚 Categories</th>
    <th>📖 Book Details</th>
  </tr>
  <tr>
    <td align="center">
      <img src="<!-- Add Home Screenshot URL -->" alt="Home Screen" width="300" />
    </td>
    <td align="center">
      <img src="<!-- Add Categories Screenshot URL -->" alt="Categories Screen" width="300" />
    </td>
    <td align="center">
      <img src="<!-- Add Book Details Screenshot URL -->" alt="Book Details Screen" width="300" />
    </td>
  </tr>
</table>

---

## 📜 License

This project is licensed under the **MIT License**.  
📄 See the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgments

- 💡 Built with [Jetpack Compose](https://developer.android.com/jetpack/compose)
- 🔥 Powered by [Firebase](https://firebase.google.com/)
- 🛠️ Dependency Injection via [Hilt](https://developer.android.com/training/dependency-injection/hilt-android)








