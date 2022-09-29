# burc
import java.util.Scanner;
public class Main {
    public static void main (String[]args){
        int month, day;
        String burc= "";
        boolean isError= false;

        Scanner input= new Scanner(System.in);
        System.out.println("Doğduğunuz ay: ");
        month=input.nextInt();

        System.out.println("Doğduğunuz gün: ");
        day= input.nextInt();

        switch (month){
            case 1=
                    if (day>=1 && day<= 31) {
                        if (day < 22) {
                            burc = "oğlak";
                        } else {
                            burc = "kova";
                        }
                    }else {
                        isError= true;
                        }
                        break;
            case 2=
                if (day>=1 && day<= 28) {
                    if (day < 28) {
                        burc = "kova";
                    } else {
                        burc = "balık";
                    }
                }else {
                    isError= true;
                }
                break;
                if (isError){
                    System.out.println("hatalı giriş yaptınız");
                }else {
                    System.out.println("burcunuz:");
                }
        }
    }
