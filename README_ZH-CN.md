# ESP32 MultiBoard Studio 2.5.0

面向 ESP32-C3/S3 的 Windows/Linux 开发工作室，基于 React、FastAPI 和 MicroPython，把板卡管理、烧录、网络和诊断集中到一个界面。

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
