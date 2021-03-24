## Отчёт о тестировании Precision

18.03.2021 было проведено тестироание приложения Precision

На тестирование затрачено: 10 минут

В результате тестирования выявлены следующие дефекты:

"C:\Program Files\Java\jdk-11.0.2\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.3.2\lib\idea_rt.jar=52860:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.3.2\bin" -Dfile.encoding=UTF-8 -classpath "C:\Users\yulia\OneDrive\Документы\JAVA homework\Задание2.2\out\production\Задание2.2" Main

0.8999999999999999

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

[issues](https://github.com/TakkiDakki/Number2.2/issues/1)

