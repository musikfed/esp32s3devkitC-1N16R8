# ESP32 MultiBoard Studio 2.5.0

ESP32-C3/S3 хавтангийн Windows/Linux хөгжүүлэлтийн студи. React, FastAPI, MicroPython дээр board удирдлага, flash, сүлжээ, оношлогоог нэг дор нэгтгэнэ.

## Architecture / Архитектура

```text
Browser/React UI -> FastAPI host service -> serial/network tools -> ESP32-C3/S3 boards running MicroPython
```

## Project structure / Структура проекта

- `frontend/` — React UI
- `host/` — host-side services
- `device/` — device configuration
- `boards/` — ESP32 board profiles

## Contact / Контакты

- Email: feudor.lab@yandex.ru
- Telegram: @Feudorlab1
