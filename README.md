# ConvertToWeb
простой конвертер из .png .jpg .jpeg .bmp в webp на пайтон в форме модуля  
\\\  
simple converter from .png .jpg .jpeg .bmp to webp

# для работы необходимы - python 3.12 и ниже, библиотека PIL (pillow)

# написан классом
является модулем, возможно встроить на сервере для автоматического преобразования файлов пользователей в более эффективный формат

# имеет управление 
через инит главного класса, возможно установить необходимые пользователю значения (форматы для поиска, директории откуда брать и куда ложить), в противном случае они стоят по умолчанию 
директория ввода называется "input"  
директория вывода называется "output"

# как использовать? - 
converter = ConvertToWeb( тут происходит установка ваших значений (оставьте пустым для значений по умолчанию) )  
converter.to_webp()

