
 **Finding runway length**

    import java.util.*;

    public class TestClass {

        public static void lcm(int a, int b){

          int max, step, lcm = 0;

          if(a > b){

             max = step = a;

          } else{

             max = step = b;

          }

          while(a!= 0) {

             if(max%a == 0 && max%b == 0) {

                lcm = max;

                break;

             }

             max += step;

          }

          System.out.println(""+lcm);

       }

       public static void gcd(int a,int b){

          int i, hcf = 0;

             for(i = 1; i <= a || i <= b; i++) {

                if( a%i == 0 && b%i == 0 )

                hcf = i;

             }

             System.out.println(""+hcf);

       }

       public static void main(String args[]){

          Scanner sc = new Scanner(System.in);

          int a = sc.nextInt();

          int b = sc.nextInt();

          gcd(a,b);

          lcm(a, b);

    }

    }
 
  **Leap Year**


