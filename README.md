# goit-nodeJS-hw01
Работа с файловой системой в Node.js, парсинг аргументов командной строки на примере работы со списком контактов (в формате JSON)
# Получаем и выводим весь список контактов в виде таблицы (console.table)

node index.js --action list

скриншот:https://ibb.co/72p663Y

# Получаем контакт по id

node index.js --action get --id 5

скриншот:https://ibb.co/tbkYgQH

# Добавялем контакт

node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22

скриншот:https://ibb.co/Z12VdzD

# Удаляем контакт

node index.js --action remove --id=3

скриншот:https://ibb.co/gzQ5nxN
