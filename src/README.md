# Отчёт о тестировании <Credit Card Number Validator>

## Реализовать функциональность валидации номера банковской карты.

08.04.2021 - 08.04.2021 было проведено ручное тестирование с использованием приложения IntelliJ IDEA

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:

*При проверки карт платежной системы American Express (AMEX) в коде ответа возникает FAIL.
* [Issue](https://github.com/EvgeniaRodi/Credit-Card-Number-Validator/issues/1)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:

*Тест-сценарий:
1. Создать новый проект в IntelliJ IDEA
2. Взять код из [Задачи №1](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)
3. Вставить карту для проверки с использованием ресурса [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)
4. Запустить RUN
5. Зафиксировать результат в отчете



В качестве тестовых данных использовались данные [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html) :
* 4916346352315669 Result is OK
* 2720998358788032 Result is OK
* 5133437036129354 Result is OK
* 4175009838200576 Result is OK
* 373840975752575 Result is FAIL
* 373622448939710 Result is FAIL
* 343530190986986 Result is FAIL

Тестирование производилось в следующем окружении:
* Версия и разрядность ОС: Windows 10 Pro 64x
* Версия Java "11.0.10"
  