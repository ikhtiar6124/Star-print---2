# Star-print---2
package star.print.pkg2;

import java.util.Scanner;

public class StarPrint2 {

    public static void main(String[] args) {
       
        int i,j,star;
        Scanner input=new Scanner(System.in);
        System.out.println("enter the number");
        star=input.nextInt();
        for(i=1;i<=6;i++)
        {
             for(j=1;j<=6;j++)
            {
                System.out.print("* ");
            }
             
              System.out.println(" ");
        }
        
    }
   
}
