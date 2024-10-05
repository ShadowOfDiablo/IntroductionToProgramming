Какво ще се изпечата:

1) 
```C++
#include <iostream>

int main()
{
  int first = 5;
  int second = 4;
  std::cout << first / second * 5;
}
```
2) 
```C++
#include <iostream>

int main()
{
  int first = 14;
  int second = 2;
  std::cout << (first / second) % 3; // процентно деление как работи
}
```
3) 
```C++
#include <iostream>

int main()
{
  double first = 4.5;
  double second = 4.3;
  int result = first - second; 
  std::cout << result;
}
```
4) 
```C++
#include <iostream>

int main()
{
  bool var = false;
  std::cout << (var || true) << std::endl;
  std::cout << var || true << std::endl; // приоритет
  std::cout << !(var && true || 0);
}
```
5)
```C++
#include <iostream>

int main()
{
  int num = 10;
  std::cout << (num / !num); // еквиваленстно на (число / 0)

  std::cout << ((num - 2) || (num / !num)); // първото има стойност различна от 0,
  компилаторът не проверява второто, защото няма значение какво е винаги ще бъде истина, т.е.
  не достига до делението на 0
}
```
6)
``` c++
  int main()
  {
    float A = 5 / 9;
    float B = 5.0 / 9.0;
    float C = 5.0 / 9;
    float D = 5 / 9.0;
    std::cout << "A = "<< A << std::endl << "B = "<< B << std::endl << "C = "<< C << std::endl << "D = "<< D << std::endl;
    return 0;
}
```

# ЗАДАЧИ:

1) Въвежда се двуцифрено число. Да се отпечата 1, ако числото е валидна дата за месец януари. Иначе 0.

2) Въвежда се  петцифрено число. Да се намери огледалното на него.
  
3) Въвежда се цяло число n. Да се изведе дали n  се дели на 2, но не се дели на 3.

4) Да се напише програма, която чете от конзолата 2 цели числа a и b и отпечатва остатъка и частното при делението им.

Вход: 
```
Enter Devident : 20
Enter Devisor : 3
```
Изход:
```
Quotand: 6
Remainder: 2 
```
5) Въвежда се четирицифрено число. Изпечатайте "True", ако е палиндром и "False", ако не е.

6) Въвежда се число в мерна единица км. Отпечатайте на колко мили се равнява. (1km = 0.621371 miles) // като константа

7) Да се напише програма, която приема 4 цели числа и отпечатва 1, ако числата образуват геометрична прогресия в реда, в който са въведени, и 0, ако съответно не образуват.

8) Въвеждат се 3 цели числа. След това се печата 1, ако поне едно от тях е било отрицателно

9) Да се въведат от конзолата коефициенти за полином от втора степен ax^2 + bx + c, както и реално число x. Да се изчисли стойността на полинома за въведената стойност.


 # Бонус задачи:
 
10)  Да се напише програма, която чете от конзолата брой секунди и изчислява колко дни, часове, минути и секунди са.

11) Да се прочетат от конзолата 4 реални числа - a, b, c, d. Да се изведе дали интервалите [a, b] и [c, d] се пресичат.//!!

12) Да се напише програма, която чете от конзолата 2 реални числа и разменя стойностите им без допълнителна промелнива.
    
13) Разликата между префиксни и постфиксни оператори за събиране/изваждане.


14) От конзолата се въвеждат 4 цели числа. Да се изведе сумата на четните числа.

Пример:
Вход:
```
17 4 63 78
```
Изход:
```
21
```
