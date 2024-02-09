import java.util.Scanner;

public class Deliver {
    public static void main(String[] args) {

        Scanner s = new Scanner(System.in);

        System.out.println("Enter the # of packages delivered: ");
        int one = s.nextInt();
        while(one<0){
            System.out.println("Enter the # of packages delivered: ");
            one = s.nextInt();
        }

        System.out.println("Enter how many collisions happened: ");
        int two = s.nextInt();
        while(two<0){
            System.out.println("Enter how many collisions happened: ");
            two = s.nextInt();
        }

        for(int i=0; i<1; i++){
            int total = (50*one) - (two*10);
            if(one>two){
                total+=500;
            }
            System.out.println(total);
        }
    }
}
