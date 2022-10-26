# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Лабораторная работа №2 - сбор, обработка и визуализация тестового набора данных

Отчет по лабораторной работе #2 выполнил(а):
- Кошелева Татьяна Алексеевна
- НМТ-213929
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | # | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Цель работы
Познакомиться с программными средствами для организции передачи данных между инструментами google, Python и Unity

## Задание 1
### Реализовать совместную работу и передачу данных в связке Python - Google-Sheets – Unity.
- В облачном сервисе google console подключить API для работы с google sheets и google drive.
- Реализовать запись данных из скрипта на python в google-таблицу. Данные описывают изменение темпа инфляции на протяжении 11 отсчётных периодов, с учётом стоимости игрового объекта в каждый период.
- Создать новый проект на Unity, который будет получать данные из google-таблицы, в которую были записаны данные в предыдущем пункте.
- Написать функционал на Unity, в котором будет воспризводиться аудио-файл в зависимости от значения данных из таблицы.

### Ход работы:
- Сохранение данных в GoogleSheets
![1](https://user-images.githubusercontent.com/114426437/198115331-c750c808-ab32-45d9-949c-4393a926ba52.png)

- Код для создания данных в GoogleSheets
![2](https://user-images.githubusercontent.com/114426437/198115557-527b134a-3b16-40dc-bf00-3ca454537217.png)

- Код для вызова звука в Unity
![3](https://user-images.githubusercontent.com/114426437/198116195-8d9a5af9-e8d5-4fe9-bce9-9ef1aec151fe.png)
![4](https://user-images.githubusercontent.com/114426437/198115692-0953a198-4699-47e6-9ec1-217339c0b1be.png)
![5](https://user-images.githubusercontent.com/114426437/198115708-5fa4e45d-1c39-4a5b-b3da-a23582c02b95.png)
![6](https://user-images.githubusercontent.com/114426437/198115747-cfd205e3-1767-4dfe-87a7-c354c8cc0a84.png)

- Демонтрация работы в Unity
![7](https://user-images.githubusercontent.com/114426437/198116253-d9fa05f6-082d-4670-94b6-b2c3f8a8bb42.png)

## Задание 2
### Реализовать запись в Google-таблицу набора данных, полученных с помощью линейной регрессии из лабораторной работы № 1.

### Ход работы:
![8](https://user-images.githubusercontent.com/114426437/198117111-3d78a5e2-304f-449a-af5a-414d339d5cdb.png)
![9](https://user-images.githubusercontent.com/114426437/198117127-f6c94515-f6cf-4d3c-b891-cfbcf02d7077.png)
![10](https://user-images.githubusercontent.com/114426437/198117039-b8bc2010-2aa0-44f7-9a81-a7145f5dca16.png)
![11](https://user-images.githubusercontent.com/114426437/198117050-079ee54b-cede-405c-86d5-7cece9cc112e.png)

### Результат работы:
![12](https://user-images.githubusercontent.com/114426437/198118699-22dc75d5-5cb8-4304-87c9-7c4284693003.png)

## Вывод
В данной лабораторной работе была изучена работа в связке Python - GoogleSheets - Unity, реализованы звуковые эффекты в Unity в зависимости от значений в GoogleSheets, реализована запись значений из первой лабораторной работы в таблицы.
