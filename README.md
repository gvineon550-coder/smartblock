[![Build SmartBlock](https://github.com/gvineon550-coder/smartblock/actions/workflows/build.yml/badge.svg)](https://github.com/gvineon550-coder/smartblock/actions/workflows/build.yml)

# SmartBlock

Быстрый и умный DNS-фильтр для Android. Блокирует рекламу, трекеры и вредоносные сайты без root-прав, используя локальный VPN. Никакие ваши данные не покидают устройство.

## Возможности
- Блокировка рекламы и трекеров на уровне DNS
- Поддержка DNS-over-HTTPS (DoH) и обычного UDP DNS
- Белый и чёрный списки с импортом из файла или URL
- Автообновление списков раз в сутки
- Исключение приложений из VPN (Per-App VPN)
- Статистика, логи и встроенная диагностика
- Автозапуск после перезагрузки телефона
- Экспорт и импорт настроек в JSON

## Установка
Скачайте последний APK из раздела **[Releases](https://github.com/gvineon550-coder/smartblock/releases)**.

## Как пользоваться
1. Откройте приложение, включите тумблер «Включить защиту».
2. Разрешите Android создать VPN-подключение.
3. Нажмите «Обновить списки» — загрузятся базы рекламы и трекеров.
4. Готово. Приложение работает в фоне и фильтрует рекламу во всех приложениях.

Более подробная инструкция доступна прямо в приложении на экране «О приложении».

## Источники данных
- [StevenBlack Hosts](https://github.com/StevenBlack/hosts)
- [AdGuard DNS Filter](https://github.com/r-a-y/mobile-hosts)
- [URLHaus](https://urlhaus.abuse.ch/)

## Лицензия
GNU General Public License v3.0. См. файл [LICENSE](LICENSE).
