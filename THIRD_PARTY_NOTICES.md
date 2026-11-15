# Сторонние компоненты и лицензии

IPA LOVE распространяется как составное произведение по лицензии
[GNU GPL v3.0](LICENSE). В сборки входят следующие компоненты:

| Компонент | Версия | Лицензия | Исходный код |
|---|---:|---|---|
| ipatool Go core | версия репозитория | MIT | https://github.com/majd/ipatool |
| pymobiledevice3 | 11.41.2 | GPL-3.0-or-later | https://github.com/doronz88/pymobiledevice3 |
| pytun-pmd3 | 3.0.3 | GPL-3.0-or-later | https://github.com/doronz88/pytun-pmd3 |
| Removed-app catalog | RestoreIPA | GPL-3.0 | https://github.com/WeirdPhrog/RestoreIPA |
| Wintun (только Windows) | в составе pytun-pmd3 | Wintun Prebuilt Binaries License | https://www.wintun.net |
| PyInstaller | 6.22.3 | GPL-2.0-or-later с исключением для bootloader | https://github.com/pyinstaller/pyinstaller |
| Wails | 2.10.2 | MIT | https://github.com/wailsapp/wails |

Тексты лицензий ipatool (MIT) и Wintun приведены в каталоге
[`licenses/`](licenses/). Лицензии остальных компонентов опубликованы в их
upstream-проектах и в метаданных пакетов.

Встроенный установщик iPhone — отдельный вспомогательный исполняемый файл,
собранный из pymobiledevice3 с помощью PyInstaller; его реализация не является
копией RestoreIPA. Каталог удалённых приложений основан на данных RestoreIPA.

Полный исходный код IPA LOVE можно получить по запросу — см.
[SOURCE_OFFER.md](SOURCE_OFFER.md).
