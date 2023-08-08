# PalindromNumber
here is a code of PalindromNumber in java.

import java.util.*;
public class palindrom {
    public static void main(String[] args) {
        
    
    Scanner sc = new Scanner(System.in);
    System.out.println("enter a no");
    int n = sc.nextInt();
    while(n>0){
        int Palindrom = n%10;
        System.out.print(Palindrom);
        n = n/10;
    }
}
}

