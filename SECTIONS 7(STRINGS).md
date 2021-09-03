**PALINDROME CHECK**

     import java.io.*;
    import java.util.Scanner;
    public class TestClass {
       public static void main(String[] args) { 
        Sample.getInput();
      }
    }
    class Sample{
      static void getInput(){
        String str=new Scanner(System.in).next();
        checkPalindrome(str);
      }
      static void checkPalindrome(String str){
        String s1=new StringBuilder(str).reverse().toString();
        if(str.equals(s1))
          System.out.print("string is a palindrome");
        else
          System.out.print("string is not a palindrome");
      }
    }
