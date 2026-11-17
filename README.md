# Umbra by DUDOS — клиенты

Официальные сборки **Windows** и **Android** для Umbra by DUDOS.

## Скачать

1. **Сайт (предпочтительно):** [dudos.sbs → Клиенты](https://dudos.sbs/#downloads)
2. **GitHub Releases:** [последний релиз](https://github.com/Dudosity/Umbra-by-DUDOS-client/releases/latest)

Не скачивайте клиент из сторонних каналов.

## Проверка

- Сверьте **SHA256** с файлом `SHA256SUMS` в релизе и с блоком на сайте.
- Отчёты **VirusTotal** по хешу файла указаны в описании релиза и на сайте.

## VirusTotal (v0.2.0)

| Файл | VirusTotal |
|------|------------|
| `umbra-windows.exe` | [отчёт по хешу](https://www.virustotal.com/gui/file/b8c7e96c0d2b6953fa030b2af53764ebbf3769c8555fe8fa59d7221e8ec8fbd0) |
| `umbra-android.apk` | [отчёт по хешу](https://www.virustotal.com/gui/file/c098eda01dc1190fe446061f176307142e697ab444c8010622dea8247f7bb5d4) |

Сканирование выполняется при каждом релизе (ссылки стабильны по SHA256). Единичные эвристики на неподписанном Windows exe возможны — крупные AV обычно чистые.

## Предупреждения ОС

Windows SmartScreen и установка Android «из неизвестного источника» нормальны без Authenticode / Google Play. Это не признак вируса само по себе — якорь доверия: домен `dudos.sbs`, GitHub-релиз и совпадение SHA256.

## Кабинет / сервер

Control plane и серверная часть: [Dudosity/VPN](https://github.com/Dudosity/VPN).
