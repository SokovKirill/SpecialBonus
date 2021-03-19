# Отчёт о тестировании <SpecialBonus>

## Краткое описание

<10.03.2021> - <10.03.2021> было проведено <функциональное тестирование> приложения <SpecialBonus>

На тестирование затрачено: <2 часа>

### В результате тестирования выявлены следующие дефекты:
- [IntellijIDEA выдает неверный результат при сложении двух нецелых чисел](https://github.com/SokovKirill/SpecialBonus/issues/1)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* <public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}>

Тестирование производилось в следующем окружении:
* <Windows 11, x64>
* <Java 11>
