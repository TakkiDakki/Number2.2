## Отчёт о тестировании Precision

18.03.2021 было проведено тестироание приложения Precision

На тестирование затрачено: 10 минут

В результате тестирования выявлены следующие дефекты:
https://github.com/TakkiDakki/Number2.2/issues/1

В качестве тестовых данных использовались данные приведенные в задании:
``` public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
} 
```
#### Тестирование производилось в следующем окружении:

* openjdk version "11.0.10" 2021-01-19
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.10+9)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.10+9, mixed mode)


