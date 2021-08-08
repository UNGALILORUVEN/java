**1).Counting number of digits**
    
    import java.util.Scanner;
    public class TestClass {
      public static void main(String args[]){
          Scanner sc = new Scanner(System.in);
          int count = 0;
          int num = sc.nextInt();
          while(num!=0){
             num = num/10;
             count++;
          }
          System.out.println(count);
       }
    }

**2).Even or Odd using division '/' operator**

     import java.io.*;
    import java.util.Scanner;
    public class TestClass {
       public static void main(String[] args) { 
           Scanner sc=new Scanner(System.in);
           int a=sc.nextInt();
           if(a%2==0)
           {
             System.out.print("Even");
           }
           else
           {
             System.out.print("Odd");
           }

      }
    }
    
**3).
