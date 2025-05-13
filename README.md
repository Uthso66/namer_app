### 📛 Namer App

A simple, responsive Flutter application built using `english_words` and `provider` packages. This app displays random English word pairs and allows users to mark their favorites. It supports navigation between the main generator and favorites list using a responsive layout with `NavigationRail`.

---

## 📦 Features

* 🔀 Random word pair generator
* ❤️ Favorite toggle with persistent UI state
* 📱 Responsive layout (mobile + tablet)
* 🎨 Theming with Material 3 and custom color scheme
* 🧠 State management with `Provider`

---

## 🚀 Getting Started

### Prerequisites

* Flutter SDK installed
* Dart SDK
* An emulator or physical device
* `provider` and `english_words` packages installed via `pubspec.yaml`

### Run the App

```bash
flutter pub get
flutter run
```

---

## 🧠 Architecture

* `MyAppState` → Handles state logic (current word pair & favorites)
* `GeneratorPage` → Displays random words and interaction buttons
* `FavoritesPage` → Lists favorite word pairs
* `NavigationRail` → Enables page switching between Generator and Favorites

---

## 📸 Screenshots
![Screenshot From 2025-05-13 19-46-19](https://github.com/user-attachments/assets/13e9bb60-3dee-4ee4-b8a5-74e505adccf6)

![Screenshot From 2025-05-13 19-46-43](https://github.com/user-attachments/assets/506004db-f9d4-43d6-ab26-d5df4528efe2)
![Screenshot From 2025-05-13 19-47-02](https://github.com/user-attachments/assets/bcee39f6-852e-4388-bad9-c4dcf2709803)


---

## 🛠️ Technologies Used

* [Flutter](https://flutter.dev/)
* [Dart](https://dart.dev/)
* [Provider](https://pub.dev/packages/provider)
* [english\_words](https://pub.dev/packages/english_words)

---

## 🙋‍♂️ Author

* Uthso
* Software QA Engineer & Flutter Apprentice

---

## 📜 License

MIT License. Use freely and learn from it.
