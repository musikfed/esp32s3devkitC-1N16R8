# Изображения витрины · PL Code Store

Скриншоты и обложки **этого проекта** хранятся прямо в `vitrine/`:

- `screenshots/main.jpg` или `screenshots/main.png` — настоящее изображение работающего интерфейса, если есть.
- `screenshots/desktop.png`, `screenshots/settings.webp` — дополнительные экраны.
- `generated/cover.svg` — помеченная иллюстративная обложка при отсутствии снимка.
- `meta.json` — описание, версия, теги, массив `screenshots`, разрешение на публикацию.

Пример в `meta.json`:

```json
{
  "screenshots": [
    "vitrine/screenshots/main.jpg",
    "vitrine/screenshots/settings.webp"
  ]
}
```

Пути указаны относительно корня Git-репозитория. Первый снимок становится основным.
Не добавляйте изображения с паролями, токенами, персональными контактами.
Положить файл можно через GitHub **Add file → Upload files**, находясь в нужной ветке и папке `vitrine/screenshots/`.
Оригинальный код проекта PL Code Store не изменяет.

Полный стандарт: https://github.com/musikfed/PLCodeStore/blob/main/docs/VITRINE_MEDIA.md

Решение автора о публикации публичного проекта — **Merge Pull Request** с изменениями vitrine/.
