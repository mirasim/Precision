# Отчёт о тестировании приложения "Precision"

## Краткое описание

Проверка расчета бонусной системы для новых клиентов компании.

## Описание тестов

1 шаг: Регулярный бонус 0.3

2 шаг: Специальный бонус для новых клиентов 0.6

3 шаг: Сложить два бонуса

* Ожидаемый результат: 0.9
* Фактический результат: 0.8999999999999999

## Результаты

1. Провели единственый тест и он не успешный.
2. [Ошибка вычисления бонуса ](https://github.com/mirasim/Precision/issues/1)

## Общие рекомендации

Рекомендую доработать данное изменения в коде. И разработчику ознакомится с особенностями выполнения арифмитических опереций над числами типа double. 