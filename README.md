# GK MOS Updates

Канал обновлений для приложения **ГК МОС Ценообразование**.

Приложение читает `latest.json` из этой ветки `main` и сравнивает `buildId` с локально установленным. Даже если `version` та же (например `0.2.0`), новый `buildId` означает, что нужно поставить свежий setup.

## latest.json

```json
{
  "version": "0.2.0",
  "buildId": "20260715-233000",
  "publishedAt": "2026-07-15T20:30:00Z",
  "fileName": "ГК_МОС_Setup_0.2.0.exe",
  "downloadUrl": "https://github.com/xWooshieL/gk-mos-updates/releases/download/...",
  "sha256": "",
  "notes": "Кратко что изменилось",
  "mandatory": false
}
```

Публикация: скрипт `app/tools/publish-update.ps1` в основном репозитории.
