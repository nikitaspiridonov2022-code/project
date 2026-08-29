# Cryptogram Android

Это Android Studio проект Cryptogram на основе текущего HTML-прототипа.

## GitHub Actions

1. Загрузите **содержимое этой папки** в корень нового GitHub-репозитория.
2. Сделайте Commit changes в ветку `main`.
3. Откройте **Actions → Build Cryptogram APK**.
4. Дождитесь зелёного завершения.
5. Откройте завершённый запуск → **Artifacts → Cryptogram-debug-apk**.
6. Скачайте ZIP из Artifacts и достаньте APK.

Workflow уже настроен на:
- Java 17
- Android SDK 35
- Build Tools 35.0.0
- Gradle 8.7
- сборку `:app:assembleDebug`

## Иконка

Добавлена иконка Cryptogram с красным бумажным самолётиком.

## Важно

Это клиент/прототип, а не копия серверной инфраструктуры Telegram. Для настоящего многопользовательского мессенджера нужны собственный сервер, база данных, авторизация, хранение сообщений, медиа, WebSocket/API и система прав.
