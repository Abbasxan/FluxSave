# Flux Save Downloader

**Flux Save** — бесплатный Android-загрузчик видео и аудио с популярных платформ. Без регистрации, без подписок.

Скачивайте контент по ссылке, выбирайте качество, управляйте загрузками в фоне и смотрите файлы во встроенном плеере.

---

## Поддерживаемые платформы

| Платформа | Поддержка |
|-----------|-----------|
| YouTube | ✅ |
| TikTok | ✅ |
| Instagram | ✅ |
| Pinterest | ✅ |
| Facebook | ✅ |

---

## Возможности

- **Вставка ссылки** — автоматическое определение платформы и доступных форматов
- **Выбор качества** — от 144p до 1080p или только аудио (MP3)
- **Фоновые загрузки** — файлы скачиваются, даже когда приложение свёрнуто
- **Встроенный плеер** — просмотр видео и прослушивание музыки
- **Буфер обмена** — автоопределение ссылок при копировании (можно отключить)
- **История загрузок** — поиск по прошлым загрузкам
- **Статистика** — личная и глобальная
- **Темы** — светлая и тёмная
- **Языки** — русский, английский, азербайджанский

---

## Скриншоты

> Скриншоты будут добавлены в следующих релизах.

---

## Технологии

- **Kotlin** + **Jetpack Compose** (Material Design 3)
- **Hilt** — dependency injection
- **Room** + **DataStore** — локальное хранение
- **WorkManager** — фоновые загрузки
- **Media3 (ExoPlayer)** — воспроизведение медиа
- **yt-dlp** + **FFmpeg** + **aria2c** — загрузка и обработка
- **NewPipeExtractor** — извлечение метаданных
- **Firebase** — аналитика и глобальная статистика

---

## Требования

- Android 8.0 (API 26) и выше
- Подключение к интернету

---

## Установка

APK и релизы публикуются на [APKPure](https://apkpure.com) и в GitHub Releases.

```bash
# Сборка debug APK
./gradlew assembleDebug

# Сборка release APK
./gradlew assembleRelease

# Сборка App Bundle для Google Play
./gradlew bundleRelease
```

---

## Политика конфиденциальности

https://abbasxan.github.io/FluxSave/

---

## Open-source компоненты

| Компонент | Лицензия |
|-----------|----------|
| yt-dlp (youtubedl-android) | GPLv3 |
| NewPipeExtractor | GPLv3 |
| OkHttp | Apache 2.0 |
| Coil | Apache 2.0 |
| AndroidX Jetpack | Apache 2.0 |
| Hilt / Dagger | Apache 2.0 |
| Media3 ExoPlayer | Apache 2.0 |

---

## Ответственное использование

Flux Save предназначен для **личного использования**. Пользователь несёт ответственность за соблюдение авторских прав и условий использования платформ-источников.

---

## Контакты

- **Разработчик:** [abbasxan](https://github.com/abbasxan)
- **Email:** Sultanov.mbk@gmail.com
- **Пакет:** `com.neonxprime.fluxsave`

---

## English

**Flux Save Downloader** is a free Android app to download videos and audio from YouTube, TikTok, Instagram, Pinterest, and Facebook. Choose quality (144p–1080p or MP3), download in the background, and play files in the built-in player. No account required.

**Privacy Policy:** https://abbasxan.github.io/FluxSave/
