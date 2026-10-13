# ESP32 MultiBoard Studio 2.5.0

ESP32-C3/S3 बोर्डों के लिए Windows/Linux विकास स्टूडियो, React, FastAPI और MicroPython पर आधारित। यह बोर्ड प्रबंधन, फ्लैशिंग, नेटवर्क और निदान को एक इंटरफ़ेस में जोड़ता है।

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
