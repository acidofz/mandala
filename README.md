# Мандала

Android-приложение с мандалой целей по методу Отани: сетка 9×9, 3 задачи на день, серия дней.

- Интерфейс: `app/src/main/assets/www/index.html` (всё в одном файле, работает офлайн).
- Обёртка: `MainActivity.java` — WebView без доступа к интернету.
- Сборка: каждый push в `main` собирает APK в GitHub Actions и выкладывает его в Releases.

Скачать: Releases → последний `build-N` → `mandala-N.apk`.

Локально: `gradle assembleDebug` (нужны JDK 17 и Android SDK 34).
