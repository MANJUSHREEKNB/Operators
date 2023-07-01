# Operators
//FENCING THE GROUND
//SOURCE CODE:
import java.io.*;
import java.util.*;
public class Solution {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        int len=2*(a+b);
        int area=a*b;
        System.out.println("The required length is "+len+" m");
        System.out.println("The required area of carpet is "+area+" sqm");
    }
}

//TREASURE HUNTER
//SOURCE CODE:
import java.io.*;
import java.util.*;
public class Solution {
    public static void main(String[] args) {
        Scanner sc=new Scanner (System.in);
        int gold=sc.nextInt();
        int ben=sc.nextInt();
        int black=sc.nextInt();
        int bens=gold*ben/100;
        int gold1=gold-bens;
        int blacks=gold1*black/100;
        int other=(gold-bens-blacks)/3;
        System.out.println(bens);
        System.out.println(blacks);
        System.out.println(other);
    }
}

//TIC TAC TOE
//SOURCE CODE:
import java.io.*;
import java.util.*;
public class Solution {
    public static void main (String [] args) {
        Scanner sc=new Scanner (System.in);
        int n=sc.nextInt();
        int row=(n-1)/3;
        int column=(n-1) %3;
        System.out.println(row+" "+column);
    }
}
