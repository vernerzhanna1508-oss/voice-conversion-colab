# 🎤 Voice Conversion in Colab (RVC / SoVITS)
# 🎤 Full Voice Conversion Colab (RVC WebUI + Demucs + Auto-Mix)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vernerzhanna1508-oss/voice-conversion-colab/blob/main/Voice_Conversion_Colab_Full.ipynb)
Этот репозиторий предназначен для экспериментов с заменой вокала в песнях на свой голос при помощи **Google Colab** и моделей **RVC / SoVITS**.

---

## 🚀 Возможности
- Подключение Google Drive и автоматическая организация папок.
- Загрузка файлов с телефона или компьютера.
- Разделение стемов (vocals / instrumental) через Demucs.
- Использование обученной модели RVC/SoVITS для замены вокала.
- Автосведение минуса + нового вокала через FFmpeg.
- (Опционально) Sidechain-компрессия для более «радио»-звучания.

---

## 📦 Что нужно
- Аккаунт Google (для работы в Colab и хранения файлов в Google Drive).
- Записи вашего голоса (2–10 минут, формат WAV/MP3).
- Стемы `instrumental.wav` и `vocals.wav` (можно получить в Lalal.ai, UVR, Demucs и т.п.).

---

## 🗂️ Рекомендуемая структура папок в Google Drive
