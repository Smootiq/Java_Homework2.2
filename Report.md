# Отчёт о тестировании приложения "Tested1.2"

## Краткое описание
Проведено тестирование на ПО IntelliJ IDEA Community, для проверки работоспособности кода по внедрению дополнительного бонуса клиентам.

## Описание тестов
На ПО IntelliJ IDEA Community, было создано базовое приложение, для тестирования работоспособности кода
> <i> public class Main { <br>
    public static void main(String[] args) { <br>
        double regularBonus = 0.3; <br>
    double specialBonus = 0.6; <br>
    double totalBonus = regularBonus + specialBonus; <br>
    System.out.println(totalBonus); <br>
    } <br>
} </i> <br>

Проводилось позитивное тестирование функционала выполнения заданной операции.

## Результаты
Выполнив команду "Run", итоговый результат с учётом переменных типа <i>"double regularBonus"</i> и <i>"double specialBonus"</i> отличается от планируемого на 0,0000000000000001

1. 0% успешных тестов
2. Issue: https://github.com/Smootiq/Java_Homework2.2/issues/1

## Общие рекомендации
* Исправить команду вывода сообщений в консоль
> <i>System.out.println(totalBonus); </i> <br>
> 
* Проверить корректность переменной типа <i>"double"</i>