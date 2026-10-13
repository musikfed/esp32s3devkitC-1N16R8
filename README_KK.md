# ESP32 MultiBoard Studio 2.5.0

ESP32-C3/S3 платаларына арналған Windows/Linux әзірлеу студиясы. React, FastAPI және MicroPython негізінде басқару, прошивка, желі және диагностиканы біріктіреді.

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
