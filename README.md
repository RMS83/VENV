---
title: 'VENV (виртуальное окружение)'
author: 'RMS83'
---

### Создание виртуального окружения (далее VENV) через cmd:
1. На WIN жмем <kbd>WIN</kbd>+<kbd>R</kbd> для загрузки командной строки либо заходим через пуск\поиск
2. Набираем 'cmd' (тем самым вызывая коммандную строку)
3. Cоздаем папку проекта в открывшемся окне коммандой * `md C:\Name`
4. Переходим в папку проекта коммандой * `cd C:\Name`
5. В папке проекта создаем VENV коммандой * `python -m venv venv` (для MAC\LINUX * `python3 -m venv venv`)
6. Активируем VENV коммандой * `venv\Scripts\activate` (для MAC\LINUX * `source venv/bin/activate`)
7. Проверяем установленные бибилиотеки коммандой * `pip list`
8. Если необходимо обновляем сам pip коммандой * `python.exe -m pip install --upgrade pip`
9. Устанавливаем необходимые версии библиотек через  * `pip install` 
10. Создаем фаил загрузки (requirements.txt) для выгрузки библиотек VENV коммандой * `pip freeze > requirements.txt`
