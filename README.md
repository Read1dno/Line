# Line
line - bypass dpi, multifunctional GUI for zapret

## Описание

Line — это удобный и простой в использовании инструмент, который поможет вам обойти DPI и улучшить доступ к YouTube. Программа предоставляет графический интерфейс для [zapret](https://github.com/bol-van/zapret), разработанной [bol-van](https://github.com/bol-van), и добавляет новые функции, такие как автозапуск, автообновление и уникальная система конфигов.

![401000914-332924580b](https://github.com/user-attachments/assets/1aa4c9fc-2eae-4467-b38a-ce8ba9e63cb0)

## Основные Функции

- **Автозапуск**: Line автоматически запускается вместе с Windows, так что вам не нужно каждый раз запускать программу вручную.
- **Автообновление**: Line сама проверяет обновления и устанавливает их, так что у вас всегда будет последняя версия.
- **Уникальная система конфигов**: Вы можете легко настроить параметры запуска winws.exe, основной части zapret, под свои нужды.
- **Графический интерфейс**: Красивый и интуитивно понятный интерфейс, написанный на PySide6.

## Установка

### Требования
- Python 3.10.6
- Библиотеки: PySide6, psutil, requests

### Установка из исходников

1. Скачайте исходный код с [GitHub репозитория](#).
2. Установите необходимые библиотеки:
   ```bash
   pip install -r requirements.txt
   ```
3. Запустите программу:
   ```bash
   python main.py
   ```

### Установка exe файла
1. Скачайте архив с последнего релиза [GitHub репозитория](https://github.com/Read1dno/Line/releases/tag/v1.0.2).
2. Разархивируйте папку line в любое место на ПК
3. Запустите exe файл в папке line.

## Безопасность
PyInstaller: Антивирусы могут жаловаться на exe файл, так как PyInstaller имеет сигнатуры, которые не нравятся антивирусам.
Виндрайвер: Моя программа использует виндрайвер, необходимый для работы zapret, который может быть определен как вирус, хотя он безопасен.

## Конфиги
Если у вас не работает youtube/discord при включенной программе, вы уверенны что все установили правильно и в браузере поставили нужные флаги Kyber и QUIC в default (chrome://flags/), то попробуйте загрузить поочередно [конфиги](https://github.com/Read1dno/Line/tree/main/config).

### Порядок действий:
1. Выключите работу обхода: `connected -> connect`
2. Загрузите новый конфиг
3. Желательно перезапустите программу

## Ссылки
Буду рад если зайдете в мои:

[Discord](https://discord.gg/n89PDURbTg)
[Telegram](https://t.me/bloomofficialyt)

## Лицензия
Эта программа распространяется под лицензией MIT. Подробнее смотрите в файле LICENSE.
