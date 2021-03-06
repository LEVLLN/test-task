# Тестовое задание: twitter-бот

## ТЗ

### Требования:
-	Программа представляет собой консольное приложение на языке C#. 
-	Программа должна корректно обрабатывать вероятные ошибки и исключения.
-	Использование сторонних библиотек - допускается для работы с API Twitter и сериализацией.

## НЕ ТЗ

### Хочу:
- Получить статистику с последних 5 твитов какого-то аккаунта в твиттере.
- Запостить сообщение от собственного аккаунта с этой статистикой.
- *Статистика* – [частотность букв](https://ru.wikipedia.org/wiki/%D0%A7%D0%B0%D1%81%D1%82%D0%BE%D1%82%D0%BD%D0%BE%D1%81%D1%82%D1%8C), составляется по данным из твитов.
 
## Пример сообщения от собственного аккаунта:
* «@username, статистика для последних 5 твитов: {статистика}».
* {статистика} представить в виде JSON объекта {a:’0.01’, b:’0.0003’ ..} 

## ***Пожелания:***
- 	Программа запрашивает логин очередного аккаунта до ввода пустой строки
- 	Программа распознаёт логины с символом ’@’ и без него	
    - @username
    - username
* 	Вывести статистику в консоль

## P.S. Основная цель разработчика – делать что-то прикольное, поэтому не возбраняется: 
1. Писать красивый код.
2. Закладываться на масштабируемость.
3. Применение навыков работы со стандартными классами .net и сторонними библиотеками.
4. Проявление понимания ООП и SOLID.
