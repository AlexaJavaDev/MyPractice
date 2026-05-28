# MyPractice. Практика в простых вещах

## Четное и нечетное

    public static void main(String[] args) {
        System.out.println(Numbers());
    }

    public static String Numbers() {
        String result = "";
        for (int i = 1; i <= 10; i++) {
            result = result + i + " ";

            if (i % 2 == 0) {
                result = result + " Четное" + "\n";
            } else {
                result = result + " Нечетное" + "\n";
            }
        }
        return result;
    }

#### Пример вывода в консоли  
1  Нечетное  
2  Четное  
3  Нечетное  
4  Четное  
5  Нечетное  
6  Четное  
7  Нечетное  
8  Четное  
9  Нечетное  
10 Четное  


## Вывод вместо цифр FizzBuzz.
Число, которое изменяется при определенных условиях.  
Если делится на 3, то выводится Fizz,  
Если делится на 5, то выводится Buzz,  
Если делится на 3 и 5, выводится FizzBuzz.

**Важно**  
Начинать условия лучше по мере уменьшения,  
-> сначала 3 и 5  
-> потом 5  
-> потом 3  

    public static void main(String[] args) {
        System.out.println(Numbers());
    }

    public static String Numbers() {
        String result = "";
        for (int i = 1; i <= 15; i++) {

            if (i % 3 == 0 && i % 5 == 0) {
                result = result + "FizzBuzz\n";
            }
            else if (i % 5 == 0) {
                result = result + "Buzz\n";
            }
            else if (i % 3 == 0) {
                result = result + "Fizz\n";

            } else {
                result = result + i + "\n";
            }
        }
        return result;
    }

#### Пример вывода в консоли

1  
2  
Fizz  
4  
Buzz  
Fizz  
7  
8  
Fizz  
Buzz  
11  
Fizz  
13  
14  
FizzBuzz  
