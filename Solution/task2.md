# Завдання 2. Створення та запуск іншої програми (цитати)

**Стартовий код:**
``` java
public class Quotation {
  String quote = "Welcome to Sun!";
  public void display() {
    System.out.println(quote);
  }
}
```

**Результат стартового кода:**

![alt-текст](https://github.com/ppc-ntu-khpi/java-0-Zheka2025/blob/main/Solution/task2.1.png?raw=true "Результат стартового кода")


#### Замінив у файлі **Quotation.java** текст довільною цитатою та вивів ім'я того, кому вона належить:
```java
public class Quotation {
  String author = " – Ralph Waldo Emerson";
  String quote = "What you do speaks so loudly that I cannot hear what you say.";
  public void display() {
    System.out.println(quote + author);
  }
}
```
**Результат:**

![alt-текст](https://github.com/ppc-ntu-khpi/java-0-Zheka2025/blob/main/Solution/task2.2.png?raw=true "Результат зміненого кода")

-----
