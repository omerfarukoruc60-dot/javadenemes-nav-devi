import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        System.out.println("NET HESAPLAMA SISTEMINE HOSGELDINIZ 20 SORULUK SINAVINIZDAKI DOGRU VE YANLIS SAYILARINIZI LUTFEN SISTEME SIRAYLA GIRINIZ");
        System.out.println("ONCE DOGRU SAYINIZI GIRIN");
        int dogru=sc.nextInt();
        if (dogru<0||dogru>20){
            System.out.println("GECERSIZ GIRIS");
        }else{
            System.out.println("SIMDI DE YANLIS SAYINIZI SISTEME GIRIN");
            int yanlis=sc.nextInt();
        if(yanlis<0||yanlis>20 || dogru+yanlis>20){
            System.out.println("GECERSIZ GIRIS");
        }else{
            double net=dogru-(yanlis/4.0);
            int bos=20-(dogru+yanlis);
            String durum;
            if(net > 15){
                durum = "COK IYI";
                }else if(net > 10){
                durum = "IYI";
                }else if (net > 5){
                durum = "ORTA";
                }else{
                durum = "GELISTIRILMELI";
            }
            System.out.println("TOPLAM SORU SAYISI 20 DOGRU SAYINIZ "+dogru+" YANLIS SAYINIZ "+yanlis+" BOS SAYINIZ "+ bos+" NETINIZ "+net+" DURUMUNUZ "+durum);
        }
        }           
}            
}         
