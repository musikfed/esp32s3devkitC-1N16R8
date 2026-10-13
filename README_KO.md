# ESP32 MultiBoard Studio 2.5.0

ESP32-C3/S3 보드를 위한 Windows/Linux 개발 스튜디오입니다. React, FastAPI, MicroPython을 기반으로 보드 관리, 플래싱, 네트워크, 진단을 한곳에 통합합니다.

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
