## Отчёт о тестировании "Precision"

**Краткое описание** 

14.09.2020 было проведено модульное тестирование функции Precision.

На тестирование затрачено: 1 час.

В программе IDEA был написан код для проверки суммирования бонусов со следующими переменными:

double regularBonus = 0.3;

double specialBonus = 0.6;

double totalBonus = regularBonus + specialBonus;

**Ожидаемый результат:**

double totalBonus = 0.9

**Фактический результат:**

ddouble totalBonus = 0.8999999999999999

[Issue](https://github.com/AndreyShitikoff/Precision/issues/1)

**Описание процесса тестирования**

В процессе тестирования использовались следующие программы.

OpenJDK 11

В качестве тестовых данных использовались данные из [Задачи №2 - Precision](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)

Тестирование производилось в следующем окружении:

* Windows 10 PRO

* OpenJDK 11