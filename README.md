# SeleniumPlus Project

**SeleniumPlus Project** — это форк [Selenium](https://github.com/SeleniumHQ/selenium), популярной библиотеки для автоматизации браузеров, с добавлением новых функций и улучшений.

> **Важно:** Это независимый проект, не поддерживаемый официальной командой Selenium. Мы рекомендуем использовать этот проект, если вам нужны дополнительные функции или модификации, которые не доступны в основной версии Selenium.

## Что нового в SeleniumPlus Project?

SeleniumPlus добавляет следующие возможности:
- Поддержка веб-драйверов для браузеров **Яндекс.Браузер**. Список будет обновляться.
- Улучшенная поддержка новых версий браузеров.
- Оптимизация производительности для работы с несколькими браузерами одновременно.

## Поддерживаемые браузеры

- **Google Chrome**
- **Mozilla Firefox**
- **Яндекс.Браузер** (Yandex Browser)

## Установка
Для установки SeleniumPlus используйте команду:
```bash
pip install seleniumplus
```

Или клонируйте репозиторий и установите его вручную:
```bash
git clone https://github.com/Tera4Byte/SeleniumPlus-Project.git
cd SeleniumPlus-Project
pip install .
```

## Использование
Пример использования SeleniumPlus для автоматизации тестирования с Яндекс.Браузером:

Яндекс.Браузер:
```python
from seleniumplus import WebDriver

# Используем драйвер для Яндекс.Браузера
driver = WebDriver(browser="yandex")
driver.get("https://ya.ru")
print(driver.title)
driver.quit()
```

## Лицензия
SeleniumPlus использует Apache License 2.0. См. полный текст лицензии в файле LICENSE.

Авторские права
Этот проект является форком оригинального репозитория Selenium. Все авторские права на оригинальный код принадлежат команде Selenium.
