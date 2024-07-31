# sum-of-digits-in-java
import java.util.*;
class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int a=0;
        int b=0;
       while(n>0){
           a=n%10;
           b=a+b;
           n=n/10;
       }
       System.out.println("sum of digits: "+b);
    }
}
