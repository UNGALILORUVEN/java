  **Leap Year**

            import java.io.*;
            import java.util.*;
            public class TestClass {
                 public static void main(String[] args) { 
                     Scanner sc = new Scanner(System.in);
                  int year;
                  year = sc.nextInt();

                  if (((year % 4 == 0) && (year % 100!= 0)) || (year%400 == 0))
                     System.out.println(+ year + " is a leap year");
                  else
                     System.out.println(+ year + " is not a leap year");
               }
            }

**Area of Triangle**
            
        import java.io.*;
        import java.util.Scanner;
        public class TestClass
        {
           public static void main(String args[]) 
            {   

              Scanner s= new Scanner(System.in);


                 double b= s.nextDouble();
                double h= s.nextDouble();
                 System.out.println("Base Width: "+b);

              System.out.println("Height: "+h);
                           double area=(b*h)/2;
              System.out.println("Area of Triangle: " + area);      
           }
        }

**Cost of shipping**

        import java.io.*;
                import java.util.Scanner;

        public class TestClass {
            public static void main(String[] args) {
                Scanner input = new Scanner(System.in);

                double weight = input.nextDouble();
                if (weight > 50)
                    System.out.println("The package cannot be shipped.");
                else
                {
                    double costPerPound; 
                    if (weight > 0 && weight <= 1)
                        costPerPound = 3.5;
                    else if (weight <= 3)
                        costPerPound = 5.5;
                    else if (weight <= 10)
                        costPerPound = 8.5;
                    else //if (weight <= 20)
                        costPerPound = 10.5;
                    System.out.println("" +
                        costPerPound * weight);
                }
            }
        }
	
