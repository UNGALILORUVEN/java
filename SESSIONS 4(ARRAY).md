**PALINDROME PROBLEM**

    import java.util.Scanner;
    public class TestClass
    {
        static boolean checkPalindrome(String str, int s, int e) 
        { 
            if (s == e)    // If there is only one character 
                return true;  
            // If first and last characters do not match 
            if ((str.charAt(s)) != (str.charAt(e))) 
                return false;   
            // If there are multiple characters, check if 
            // middle substring is also palindrome or not. 
            if (s < e + 1) 
                return checkPalindrome(str, s + 1, e - 1);   
            return true; 
        }   
        static boolean isPalindrome(String str) 
        { 
            int n = str.length();
            if (n == 0) 
                return true;   
            return checkPalindrome(str, 0, n - 1); 
        }   
     public static void main(String args[]) 
        { 
            Scanner sc = new Scanner(System.in);
            String str = sc.nextLine();
            if (isPalindrome(str)) 
                System.out.println(str+" is a palindrome"); 
            else
                System.out.println(str+ " is not a palindrome"); 
        }   
    }
