import java.util.Scanner;
public class ChiliPeppers {
    public static void main(String args[]) {

        Scanner s = new Scanner(System.in);
        String a;
        int num;
        int total=0;

        System.out.println("Enter number of peppers: ");
        num = s.nextInt();


        for(int i=0; i<num; i++){
            System.out.println("Enter the peppers you added: ");
            a = s.nextLine();

            if(a.equals("Poblano"))
                total += 1500;
            if(a.equals("Mirasol"))
                total += 6000;
            if(a.equals("Serrano"))
                total += 15500;
            if(a.equals("Cayenne"))
                total += 40000;
            if(a.equals("Thai"))
                total += 75000;
            if(a.equals("Habanero"))
                total += 125000;

        }
        System.out.println(total);

    }
}
