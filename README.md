# Discord-Selfbot
Многофункциональный селф-бот написанный на discord.py.

Так как дискорд запретил эмбеды, пришлось переписывать селф бота. Пока-что находится в бета версии, все ошибки и идеи сообщайте мне.

# Установка
1. Устанавливаем Python 3.8 (Туториалы вы можете найти в ютубе)
2. Скачиваем [архив](https://github.com/Its-LALOL/Discord-Selfbot/archive/refs/heads/main.zip)
3. Перекидываем папку из архива на рабочий стол
4. Открываем папку
5. В папке открываем файл config.json через блокнот
6. Записываем токен после `"Token": ` в ковычках ([Туториал по получению токена](https://youtu.be/CE1_h7nKJx0))
7. Запускаем файл start.bat
8. Готово

# Пишет "Invalid Token!", хотя токен рабочий или выдаёт ошибку
1. Откройте командную строку
2. Напишите туда `pip uninstall discord.py discord discord.py-self`
3. Запустите файл start.bat

# Туториал как загрузить бота на replit.com
1. Загрузите селф бота в свой репл
2. Создайте файл `a.txt` и запишите в него слово `discord`
3. Зайдите в main.py
4. После строки `import os` вставьте следующий код
```python
os.system("pip uninstall a.txt")
os.system("pip install -U discord.py-self")
```
5. Готово

# ВНИМАНИЕ!
Обратите внимание, что селф боты запрещены. Если вас забанят, то виноваты будете только ВЫ!
Программа создана только для образовательных целях!
