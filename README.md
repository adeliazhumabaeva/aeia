import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        String a= "У меня";
        String b="апельсина";
        var num=5;
        String c=a+num+b;
        System.out.println(c);

        final String VILLAGE="Karakol";
        System.out.println(VILLAGE);

        String word="Kyrgyzstan";
        System.out.println(word);

        System.out.println(+num+word);
        System.out.println(a+b+VILLAGE);
        int num1 = 2;
        int value;


        switch (num1){
            case 1:
                System.out.println("вы сохранили отрицательное число");
                break;
            case 2:
                System.out.println("вы сохранили + число");
                break;
            case 3:
                System.out.println("вы сохранили 0");
                break;
            default:
                break;

                


        }

        System.out.println("Введите ваше имя:");
        String name = in.nextLine();
        System.out.println("Введите ваше имя:\t"+name);

        System.out.println("\tДобро пожаловать!");
    }
}
