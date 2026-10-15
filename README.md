<div align="center">

# Recipes App
# 🍳

### A React Native app for browsing recipes

A mobile recipes desk with a splash screen, home, categories, search, a recipe page, and ingredient details. Navigation is a drawer plus a stack.

<br>

# 👨‍💻 **Sadra Hatami**

### *Developer • Software Engineer • Creator*

<br>

[![React Native](https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactnative.dev/)
[![Expo](https://img.shields.io/badge/Expo-36-000020?style=for-the-badge&logo=expo&logoColor=white)](https://expo.dev/)
[![React](https://img.shields.io/badge/React-16.9-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![React Navigation](https://img.shields.io/badge/React%20Navigation-5-6C47FF?style=for-the-badge)](https://reactnavigation.org/)
[![Drawer](https://img.shields.io/badge/Navigation-Drawer-2C3E50?style=for-the-badge)](https://reactnavigation.org/docs/drawer-navigator/)
[![Redux](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white)](https://redux.js.org/)
[![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=apple&logoColor=white)](https://developer.apple.com/ios/)
[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com/)
[![Web](https://img.shields.io/badge/Web-Expo-4630EB?style=for-the-badge&logo=expo&logoColor=white)](https://docs.expo.dev/workflow/web/)
[![Search](https://img.shields.io/badge/Screen-Search-1ABC9C?style=for-the-badge)](#-screens)
[![Categories](https://img.shields.io/badge/Screen-Categories-E67E22?style=for-the-badge)](#-screens)
[![Recipes](https://img.shields.io/badge/Screen-Recipes-C0392B?style=for-the-badge)](#-screens)
[![Ingredients](https://img.shields.io/badge/Screen-Ingredients-27AE60?style=for-the-badge)](#-screens)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/license/mit)
[![Open Source](https://img.shields.io/badge/Open_Source-Project-black?style=for-the-badge&logo=github)](https://opensource.org/)

<br>

[🌐 GitHub Profile](https://github.com/sadra-hatami)
•
[📧 Email](mailto:sadra.hatami.1732@gmail.com)

</div>

---

# 📑 Table of Contents

- [About](#-about)
- [Why This Project?](#-why-this-project)
- [Screens](#-screens)
- [Key Features](#-key-features)
- [Project Structure](#-project-structure)
- [Technologies](#️-technologies)
- [Installation](#-installation)
- [Usage](#️-usage)
- [Notes](#-notes)
- [FAQ](#-faq)
- [Contact](#-contact)
- [License](#-license)
- [Support](#-support)

---

# 📖 About

**Recipes App** is a React Native recipes browser built with Expo.

It opens on a splash screen, then a home list. From there the user can open categories, search, read a recipe, and look at ingredients. A drawer holds the side menu. Recipe data lives in local arrays, not on a server.

The project name in `app.json` is Instafood. The screen set follows that public recipes template. This repository keeps the app as a study build.

> **Tagline:** *A React Native recipes app with home, search, categories, and recipe screens.*

The console order desk in [Food Ordering System](https://github.com/sadra-hatami/Food-Ordering-System) is a separate project.

---

# 🚀 Why This Project?

A recipes app is a clean place to practice navigation and reusable screens.

This one keeps that split:

- A splash, then a home list
- Categories and search as their own screens
- A recipe page with an ingredients path
- Shared buttons and a drawer

It is a mobile study app, not a restaurant service.

---

# 📱 Screens

| Screen | Role |
|---|---|
| Splash | Opening screen |
| Home | Recipe list |
| Categories | Category browse |
| Search | Find a recipe |
| Recipes list | Recipes in a group |
| Recipe | One recipe |
| Ingredient | Ingredient view |
| Ingredients details | Ingredient detail |
| Drawer | Side menu |

---

# ✨ Key Features

- 🍳 Local recipe data
- 🔎 Search screen
- 🗂️ Categories
- 📖 Recipe and ingredient pages
- ☰ Drawer navigation
- 📲 Expo scripts for Android, iOS, and web
- 🖼️ Local icons and splash image

---

# 📁 Project Structure

```text
Recipes-App/
├── App.js
├── app.json
├── package.json
├── babel.config.js
├── assets/
└── src/
    ├── components/
    ├── data/
    ├── navigations/
    └── screens/
```

`App.js` starts the navigator. `src/data` holds the recipe arrays. `src/navigations/AppNavigation.js` wires the screens.

---

# 🛠️ Technologies

- React Native
- Expo SDK 36
- React Navigation 5
- React Native Elements
- Local JavaScript data

---

# 🚀 Installation

```bash
git clone https://github.com/sadra-hatami/Recipes-App.git
cd Recipes-App
npm install
```

---

# ▶️ Usage

```bash
npm start
```

Then open the project in Expo Go, or use:

```bash
npm run android
npm run ios
npm run web
```

Expo SDK 36 is an old SDK. A current Expo Go may refuse it. In that case use a matching older client, or upgrade the SDK before expecting a phone preview.

---

# 📝 Notes

- Recipe content is local. There is no account and no order backend.
- Do not commit `node_modules`, `.expo`, or `.DS_Store`.
- `LICENSE` from the original package is not in this repository.

---

# ❓ FAQ

### Is this the C++ food menu?

No. That one is [Food Ordering System](https://github.com/sadra-hatami/Food-Ordering-System).

### Does it need a server?

No. Screens read local data.

### Will current Expo Go open it?

Maybe not. The pinned SDK is 36.

---

# 📬 Contact

**Developer:**

### Sadra Hatami

📧 [Email](mailto:sadra.hatami.1732@gmail.com)

🌐 [GitHub](https://github.com/sadra-hatami)

---

# 📄 License

Add a `LICENSE` file if you want a formal MIT grant. The badge above points at the MIT text.

---

# ⭐ Support

If this app is useful as a study sample, please consider giving it a ⭐ on GitHub.

---

<div align="center">

## Designed & Developed with ❤️ for the developer community of Iran and the world by **Sadra Hatami**

</div>
