# MyPractice

# Мой первый код без помощи ИИ

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
                result = result + " Не четное" + "\n";
            }
        }
        return result;
    }

# Пример вывода в консоли

1  Не четное

2  Четное

3  Не четное

4  Четное

5  Не четное

6  Четное

7  Не четное

8  Четное

9  Не четное
10  Четное
