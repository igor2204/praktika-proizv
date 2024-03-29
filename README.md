# Информационная система «Краткие заметки»
Данное программное обеспечение разработано для создания, сохранения и удаления заметок в соответствующих категориях

## Содержание
- [Технологии](#технологии)
- [Использование](#использование)
- [Разработка](#разработка)
- [Тестирование](#тестирование)
- [Contributing](#contributing)
- [FAQ](#faq)
- [To do](#to-do)
- [Команда проекта](#команда-проекта)
- [Источники](#источники)

## Технологии
- [VisualStudio 2022](https://visualstudio.microsoft.com/ru/)
- [C#](https://learn.microsoft.com/ru-ru/dotnet/csharp/tour-of-csharp/)
- [.NET 6.0](https://learn.microsoft.com/ru-ru/dotnet/welcome)

## Использование
Для работы с приложением необходимо следующее программное обеспечение:

Microsoft Visual Studio Community 2022

Перед началом работы с Информационной средой «Краткие заметки» на рабочем месте пользователя необходимо выполнить следующие действия:
1. Открыть программу Microsoft Visual Studio Community 2022.
2. Найти программу «zametki».
3. Открыть ее.
4. Нажать на кнопку запуска

### Задача: «Создание, сохранение, просмотр и удаление данных»

Введите данные и нажмите на кнопку «Сохранение»
   
![image](https://github.com/igor2204/praktika-proizv/assets/117898131/7e9b7661-0530-47c5-8bd2-f62701e4f399)

Выберите нужную строку в правой таблице и нажмите кнопку «Просмотр»

![image](https://github.com/igor2204/praktika-proizv/assets/117898131/b34f7542-8786-407b-b0db-c3b7b9cdc230)

Для удаления заметки нажмите на кнопку «Удаление»

![image](https://github.com/igor2204/praktika-proizv/assets/117898131/b2faae39-4ac9-4e3f-8b63-bb05abde0884)

### Задача: «Импорт текстового файла и экспорт текста в файл»

Нажмите на кнопку «Открыть файл»

![image](https://github.com/igor2204/praktika-proizv/assets/117898131/0ae971b7-97d5-4754-8076-e977f8644ad9)

Выберите нужный текстовый файл и нажмите кнопку «Открыть»

![image](https://github.com/igor2204/praktika-proizv/assets/117898131/7f9c44b3-339b-4c14-954d-3924936bd6e1)

Наберите данные и нажмите на кнопку «Сохранить в файл»

![image](https://github.com/igor2204/praktika-proizv/assets/117898131/29a06f50-1fbd-4895-8a49-e093e47bd16c)

Выберите место для сохранения, назовите файл и нажмите на кнопку «Сохранить»

![image](https://github.com/igor2204/praktika-proizv/assets/117898131/c4b553b7-677e-47ce-a12d-f316b15c2e29)

## Разработка

### Требования
Для установки и запуска проекта, необходим [VisualStudio 2022](https://visualstudio.microsoft.com/ru/)

## Тестирование
В проекте использовались следующие виды тестирования: Интеграционное

Итоги тестирования:

### Интеграционное тестирование

![image](https://github.com/igor2204/praktika-proizv/assets/117898131/058320ff-7138-438c-b0dc-b2caba278877)

### Тестовые пути:

Т1: 1 – 2 – 10

T2: 1 – 2 – 4 – 10

Т3: 1 – 2 – 5 – 10

T4: 1 – 3 – 10

T5: 1 – 3 – 7 - 10

T6: 1 – 3 – 8 - 10

T7: 1 – 3 – 9 - 10

T8: 1 – 3 – 6 - 10

T9: 1 – 10

### Пути: 

Путь 1: Запуск приложения, работа с файлами, закрытие приложения

Путь 2: Запуск приложения, работа с файлами, сохранение в файл, закрытие приложения

Путь 3: Запуск приложения, работа с файлами, открытие файла, закрытие приложения

Путь 4: Запуск приложения, работа с данными, закрытие приложения

Путь 5: Запуск приложения, работа с данными, создание, закрытие приложения

Путь 6: Запуск приложения, работа с данными, сохранение, закрытие приложения

Путь 7: Запуск приложения, работа с данными, просмотр, закрытие приложения

Путь 8: Запуск приложения, работа с данными, удаление, закрытие приложения

Путь 9: Запуск приложения,  закрытие приложения

### Тест-кейсы

Таблица 1. Тест-кейс сохранения данных

![image](https://github.com/igor2204/praktika/assets/117898131/80a84524-1869-4a02-a589-8d21eba78cfb)

Таблица 2. Тест-кейс просмотра данных

![image](https://github.com/igor2204/praktika/assets/117898131/3c6710db-8536-43b3-be6f-61b919a247a6)

Таблица 3. Тест-кейс удаления данных

![image](https://github.com/igor2204/praktika/assets/117898131/81f03b6e-8e0e-4ffb-8293-260aaaf3da31)

Таблица 4. Тест-кейс открытия файла

![image](https://github.com/igor2204/praktika/assets/117898131/6738ff19-0f06-47e7-83cd-e86693bc906c)

Таблица 5. Тест-кейс сохранения файла

![image](https://github.com/igor2204/praktika/assets/117898131/c0195f60-8a99-41e2-abf3-29bc1155fd2d)

## Contributing
Сообщения о багах и ошибках присылать на почту: igorcomkalov@gmail.com

## FAQ 
### Где можно установить Visual Studio?
- [На официальном сайте Microsoft](https://visualstudio.microsoft.com/ru/)
### Как найти кнопку "Сохранить в файл"?
- Она находится в правой нижней части главного окна.

## To do

- [x] Работа с данными заметок, например удаление, изменение, сохранение и т.д.
- [x] Ввод данных из файла: пользователи должны иметь возможность вводить заметки в виде файла с поддержкой различных форматов, таких как .txt, .pdf или .docx.
- [x] Вывод данных в файл: приложение должно предоставлять функциональность вывода заметок из файлов предыдущего экспорта или из других источников.

## Команда проекта
- [Цомкалов Игорь](https://vk.com/id194250284) — Главный разработчик, программист, тестировщик, дизайнер

## Источники
https://metanit.com/sharp/

https://metanit.com/sharp/windowsforms/












   





   


   
