  **1).Leap Year**

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

**2).Area of Triangle**
            
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

**3).Cost of shipping**

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
	
**4).Moons gravity**

	 import java.io.*;
	import java.util.Scanner;
	public class TestClass {
		 public static void main(String[] args)
	     { 
	       Scanner s=new Scanner(System.in);
	       double weight=s.nextInt();
	       double mw=(weight*(16.6))/100;
	       System.out.println(mw);
		}
	}

**5).Even or Odd**

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

**6).
