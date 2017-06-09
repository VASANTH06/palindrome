import java.io.*;
import java.util.*;
public class Palindrome {


    public static void main(String[] args) {
        Scanner scan=new Scanner(System.in);
        int sum=0,r,temp;
        int n=scan.nextInt();
        temp=n;
        while(n>0)
        {
            r=n%10;
            sum=(sum*10)+r;
            n=n/10;
        }
        if(sum==temp)
        {
            System.out.println("The given num is palindrome");
           
        }
        else
        {
            System.out.println("The given number is not a palindrome");
        }
    }
    
}
