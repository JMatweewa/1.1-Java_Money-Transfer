# Отчёт о тестировании Money Transfer

## Краткое описание

27.11.2021 было проведено тестирование приложения Money Transfer.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [При пополнении счета клиента, итоговое значение суммы неверное](https://github.com/JMatweewa/1.1-Java_Money-Transfer/issues/1#issue-1065047259)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* [Пример кода, на основании которого создавалось базовое приложение](https://github.com/netology-code/javaqa-code/blob/master/1.2_programming/variables/src/Main.java)


В качестве тестовых данных использовались [входные данные](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/MERGED.md), указанные в ДЗ Задача №1 - Money Transfer:

* Текущий баланс счёта клиента: balance = 2_000_000_000
* сумма перевода (пополнение): amountToTransfer - 500_000_000
* итоговое значение: totalBalance

Тестирование производилось в следующем окружении:
* Windows 10 *64
* Java version 11.0.13+8