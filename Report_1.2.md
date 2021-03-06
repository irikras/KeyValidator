# Отчёт о тестировании "KeyValidator".

## Краткое описание

13.07.2021 было проведено функциональное тестирование приложения "KeyValidator".

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Не валидный ключ отображается как валидный](https://github.com/irikras/KeyValidator/issues/1#issue-944064320)
* [Валидный ключ отображается как не валидный](https://github.com/irikras/KeyValidator/issues/2#issue-944066959)


## Описание процесса тестирования

- Установить OpenJDK11 
- Запустить git bush
- Проверить работу приложения согласно руководству использования на валидность либо не вадидность ключей.

В качестве тестовых данных использовались данные:
* [Инструкция по установке OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md) - Приложение запускается и совместимо с Java 11
* [Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md) - Приложение работает согласно руководству 
    

Тестирование производилось в следующем окружении:
* Windows 10 Version 20H2
* Openjdk version "11.0.11" 2021-04-20

