СУПЕР АЛЕКСАНДР — подготовка к Android APK

Сейчас игра работает как автономная веб-игра: откройте www/index.html в современном браузере.

Для сборки Android-приложения на компьютере:
1. Установите Node.js LTS, Android Studio и Android SDK.
2. Распакуйте этот проект и откройте терминал в его папке.
3. Выполните: npm install
4. Выполните: npx cap add android
5. Выполните: npx cap sync android
6. Выполните: npx cap open android
7. В Android Studio выберите Build > Build Bundle(s) / APK(s) > Build APK(s).

APK здесь не собран: для этого необходимы Android SDK/Android Studio и локальная сборочная среда.
Игра использует только встроенные HTML/CSS/JavaScript и встроенный портрет; интернет для игры не нужен.
