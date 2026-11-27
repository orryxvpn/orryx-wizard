# ORRYX Wizard

Настройте ORRYX на домашнем роутере: откройте приложение, авторизуйтесь или вставьте ссылку подписки — Wizard сам найдёт роутер, определит модель и прошивку и выполнит настройку. Поддерживаются Keenetic, роутеры на OpenWrt (сотни моделей разных брендов), Xiaomi / Redmi и другие. Перед изменениями сохраняется резервная копия конфигурации, а настройку можно откатить.

## Скачать ORRYX Wizard

| Система | Скачать |
|---|---|
| macOS 13+ | [![Apple Silicon](https://img.shields.io/badge/Apple_Silicon-Скачать-147d58?style=for-the-badge)](https://github.com/orryxvpn/orryx-wizard/releases/download/v0.11.3/ORRYX-Wizard-0.11.3-macos-arm64.dmg) [![Intel](https://img.shields.io/badge/Intel-Скачать-147d58?style=for-the-badge)](https://github.com/orryxvpn/orryx-wizard/releases/download/v0.11.3/ORRYX-Wizard-0.11.3-macos-x86_64.dmg) |
| Windows x64 | [![Установщик x64](https://img.shields.io/badge/Установщик_x64-Скачать-147d58?style=for-the-badge)](https://github.com/orryxvpn/orryx-wizard/releases/download/v0.11.3/ORRYX-Wizard-0.11.3-windows-x64-setup.exe) [![Portable x64](https://img.shields.io/badge/Portable_x64-Скачать-147d58?style=for-the-badge)](https://github.com/orryxvpn/orryx-wizard/releases/download/v0.11.3/ORRYX-Wizard-0.11.3-windows-x64-portable.zip) |
| Windows 11 ARM64 · экспериментальная | [![Установщик ARM64](https://img.shields.io/badge/Установщик_ARM64-Скачать-147d58?style=for-the-badge)](https://github.com/orryxvpn/orryx-wizard/releases/download/v0.11.3/ORRYX-Wizard-0.11.3-windows-arm64-setup.exe) [![Portable ARM64](https://img.shields.io/badge/Portable_ARM64-Скачать-147d58?style=for-the-badge)](https://github.com/orryxvpn/orryx-wizard/releases/download/v0.11.3/ORRYX-Wizard-0.11.3-windows-arm64-portable.zip) |

[Все выпуски и история изменений](https://github.com/orryxvpn/orryx-wizard/releases)

Нужны сам роутер, интернет и доступ администратора роутера. Wizard проверяет роутер вживую и начинает настройку, только если модель, память, прошивка и firewall подходят. Для Keenetic может понадобиться USB-накопитель под Entware — Wizard подскажет и подготовит его.

## Какие роутеры подходят

Wizard определяет роутер сам — выбирать тип вручную не нужно. Поддерживаются:

- **Keenetic** (KeeneticOS 4+) — через Entware.
- **Роутеры на OpenWrt 21.02+ любого бренда** — сотни моделей: NETGEAR, TP-Link, ASUS, GL.iNet, Xiaomi, Ubiquiti, MikroTik, Banana Pi / NanoPi / Raspberry Pi, x86 и другие.
- **Xiaomi / Redmi на заводской прошивке** — модель Redmi AX1800 (RA71). Остальные модели Xiaomi — проверка совместимости.

Точный список моделей и то, что на них уже проверено, Wizard показывает прямо в приложении. Какая бы ни была модель, решение всегда принимает живая проверка самого роутера.

## Резервная копия

Перед настройкой выберите папку для ZIP с конфигурацией роутера; по умолчанию — рабочий стол. Штатная резервная копия и доступные файлы VPN сохраняются до изменений. Доступ к роутеру и папка сохранения находятся на одном шаге. Копию можно пропустить кнопкой «Пропустить». Если выбрано сохранение, ошибка остановит настройку. Автоматические точки восстановления на роутере сохраняются.

## Авторизация

Кнопка «Авторизоваться» открывает обычный личный кабинет ORRYX. После входа поиск роутера начинается автоматически; если подписок несколько, выберите нужную. Ручной ввод ссылки также доступен.

## Панель ORRYX

После настройки откройте локальную панель кнопкой в Wizard: живые графики трафика и соединений, выбор серверов, смена ссылки подписки с резервной копией и проверка задержки. Срок подписки отображается по данным сервиса; кнопка «Продлить» открывает кабинет. Адрес и пароль панели появятся в конце настройки.

## Обновления

Wizard автоматически проверяет наличие новых выпусков и показывает уведомление. Нажмите «Обновить», чтобы загрузить новый выпуск и перезапустить приложение после установки. При переходе с версии 0.8.1 потребуется установить новый выпуск вручную.

Предварительный выпуск. Windows ARM64 требует дополнительной проверки на нативном устройстве. Доступные возможности зависят от модели роутера и версии его прошивки.

[Личный кабинет](https://app.orryx.org) · [Помощь и поддержка](https://app.orryx.org/#/support-chat/new)
