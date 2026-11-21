# КиноСвайп

Android-приложение для выбора кино: критерии и пресеты, свайпы, журнал просмотров,
совместные комнаты по коду.

**Скачать APK:** https://kinosvape.pages.dev/apk/latest.apk
**Страница обновлений:** https://kinosvape.pages.dev

В репозитории — исходники. Бинарники и фид обновлений (`version.json`) живут на
`kinosvape.pages.dev`; GitHub Releases для раздачи приложения не используются.

## Сборка

`build_manual.ps1` собирает APK без Gradle: aapt2 -> javac -> kotlinc -> d8 -> zipalign -> apksigner.
Запускать в PowerShell 7 (`pwsh`), нужны android-sdk 35.0.0, JDK 17, kotlinc и compose-плагин.
