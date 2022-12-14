# Калькулятор римских и арабских чисел

> Это приложение создано в рамках выполнения тестового задания для [Kata Academy](https://kata.academy/java/postpayment). Это калькулятор, в котором можно совершить простые вычислительные операции.

## Вид данных для ввода
- Операция состоит из двух операндов и одного оператора
- Операнды и оператор должны быть разделены пробелами (Например: 1 + 2)
- Оба операнда должны быть либо римскими (I), либо арабскими (1)
- Возможные операторы: +, -, *, /

## Требования:
- Калькулятор умеет выполнять операции сложения, вычитания, умножения и деления с двумя числами: a + b, a - b, a * b, a / b. Данные передаются в одну строку. Решения, в которых каждое число и арифмитеческая операция передаются с новой строки считаются неверными.
- Калькулятор умеет работать как с арабскими (1,2,3,4,5…), так и с римскими (I,II,III,IV,V…) числами.
- Калькулятор должен принимать на вход числа от 1 до 10 включительно, не более. На выходе числа не ограничиваются по величине и могут быть любыми.
- Калькулятор умеет работать только с целыми числами.
- Калькулятор умеет работать только с арабскими или римскими цифрами одновременно, при вводе пользователем строки вроде 3 + II калькулятор должен выбросить исключение и прекратить свою работу.
- При вводе римских чисел, ответ должен быть выведен римскими цифрами, соответственно, при вводе арабских - ответ ожидается арабскими.
- При вводе пользователем неподходящих чисел приложение выбрасывает исключение и завершает свою работу.
- При вводе пользователем строки, не соответствующей одной из вышеописанных арифметических операций, приложение выбрасывает исключение и завершает свою работу.
- Результатом операции деления является целое число, остаток отбрасывается. 
- Результатом работы калькулятора с арабскими числами могут быть отрицательные числа и ноль. Результатом работы калькулятора с римскими числами могут быть только положительные числа, если результат работы меньше единицы, выбрасывается исключение

## Built with

- Java

## Getting Started

Чтобы скопировать проект на свой компьютер, нужны предустановленные:

- IntelliJ IDEA
- Open JDK

## Author

- GitHub: [@rdnrn](https://github.com/rdnrn)
- LinkedIn: [Nana Rodina](https://www.linkedin.com/in/arina-rodina-144612219/?locale=en_US)
- Twitter: [nana](https://twitter.com/rdnrn_nana)


