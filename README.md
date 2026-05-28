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
                result = result + " Нечетное" + "\n";
            }
        }
        return result;
    }

# Пример вывода в консоли

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
