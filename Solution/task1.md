# Завдання 1. Створення та запуск першої програми (сорочки)

Стартовий код:
``` java
public class Shirt {
  public int shirtID = 0; // стандартне значення номера моделі сорочки
  public String description = "-description required-"; // стандартний опис сорочки
  // коди кольорів: R=червоний, B=синій, G=зелений, U=невідомо
  public char colorCode = 'U';
  public double price = 0.0; // стандартна вартість сорочки
  public int quantityInStock = 0; // стандартна кількість на складі
  
  // цей метод просто виводить всю інформацію про сорочку на екран
  public void displayShirtInformation() {
    System.out.println("Shirt ID: " + shirtID);
    System.out.println("Shirt description:" + description);
    System.out.println("Color Code: " + colorCode);
    System.out.println("Shirt price: $" + price);
    System.out.println("Quantity in stock: " + quantityInStock);
  } // кінець методу displayShirtInformation
} // кінець опису класу
```

**Результат стартового кода:**

![alt-текст](https://github.com/ppc-ntu-khpi/java-0-Zheka2025/blob/main/Solution/task1.1.png?raw=true "Результат стартового кода")


Замінив у файлі Shirt.java номер сорочки, її опис та вартість довільними значеннями:
```java
public class Shirt {
  public int shirtID = 0; // стандартне значення номера моделі сорочки
  public String description = "Зелена сорочка"; // стандартний опис сорочки
  // коди кольорів: R=червоний, B=синій, G=зелений, U=невідомо
  public char colorCode = 'G';
  public double price = 100.0; // стандартна вартість сорочки
  public int quantityInStock = 50; // стандартна кількість на складі
  
  // цей метод просто виводить всю інформацію про сорочку на екран
  public void displayShirtInformation() {
    System.out.println("Shirt ID: " + shirtID);
    System.out.println("Shirt description: " + description);
    System.out.println("Color Code: " + colorCode);
    System.out.println("Shirt price: $" + price);
    System.out.println("Quantity in stock: " + quantityInStock);
  } // кінець методу displayShirtInformation
} // кінець опису класу
```
**Результат:**

![alt-текст](https://github.com/ppc-ntu-khpi/java-0-Zheka2025/blob/main/Solution/task1.2.png?raw=true "Результат зміненого кода")

-----


