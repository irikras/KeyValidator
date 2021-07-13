# Отчёт о тестировании "Credit Card Number Validator".

## Краткое описание

12.07.2021 - 13.07.2021 было проведено функциональное тестирование приложения "Credit Card Number Validator".

На тестирование затрачено: 4 часа

В результате тестирования выявлены следующие дефекты:
* https://github.com/irikras/Credit-Card-Number-Validator/issues/1#issue-943405519

## Описание процесса тестирования

Запустить программу с кодом, подставляя валидные и невалидные номера банковских карт.

В качестве тестовых данных использовались данные с сайта https://www.freeformatter.com/credit-card-number-generator-validator.html#fakeNumbers:
* Result is OK (по валидным номерам банковских карт)
* Result is FAIL (по невалидным/фейковым номерам банковских карт)

Тестирование производилось в следующем окружении:
* Windows 10 Version 20H2
* Java SE 11

