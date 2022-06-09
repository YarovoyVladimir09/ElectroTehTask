Тестовое задание для ГОРЭЛТЕХа

Разработать оконное приложение на базе MFC

Основное окно должно содержать в левой части дерево (TreeView), должно заполняться из текстового файла, выбираемого пользователем.

Формат входных данных:

"id":"pId":"caption":"status":"message"

где
- id - глобальный идентификатор
- pId - id родительской ноды
- caption - название в дереве
- status - статус ноды 
- message - текст
По двойному щелчку должен выводиться Message Box, содержащий message из ноды

Пример файла:

-0:(-1):CAP0:1:MESSAGE-0

-1:0:CAP01:1:MESSAGE-01

-2:0:CAP02:0:MESSAGE-02

-3:(-1):CAP1:1:MESSAGE-1

-4:0:CAP11:1:MESSAGE-11

-5:0:CAP12:1:MESSAGE-12

Задание выполнено по стандарту С++17, в папке TestEx лежит два файла формата txt, для проверки работоспособности

![image](https://user-images.githubusercontent.com/94742842/172691627-2f7ebcee-bca7-4428-9f98-45f4db1a34ad.png)

