# Отчёт о тестировании <Credit Card Number Validator>

## Реализовать функциональность валидации номера банковской карты.

08.04.2021 - 08.04.2021 было проведено   приложения <название приложения>.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Issue](https://github.com/EvgeniaRodi/Credit-Card-Number-Validator/issues/1)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
Тест-сценарий:
1. Создать новый проект в IntelliJ IDEA
2. Взять код из [Задачи №1](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)
3. Вставить карту для проверки с использованием ресурса [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)
4. Запустить RUN
5. Зафиксировать результат в отчете



В качестве тестовых данных использовались данные [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html) :
* <4916346352315669 Result is OK>
* <2720998358788032 Result is OK>
* <5133437036129354 Result is OK>
* <4175009838200576 Result is OK>

Тестирование производилось в следующем окружении:
* Устройство:  Windows 10 Pro 64x
* openjdk version "11.0.10" 2021-01-19
  OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.10+9)
  OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.10+9, mixed mode)
  