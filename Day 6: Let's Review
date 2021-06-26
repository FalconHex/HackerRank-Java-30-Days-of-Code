import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
        
        Scanner sc = new Scanner(System.in);
        
        int n = sc.nextInt();
        sc.nextLine();
        
        for(int i=0; i<n; i++){
            
            String word = sc.nextLine();
            String oddWord = "";
            String evenWord = "";
            
            int num = word.length();
            
            for(int j=0; j<num; j++){
                
                if(j%2==0)
                evenWord += word.charAt(j);
                
                else
                oddWord += word.charAt(j);
                
            }
            System.out.println(evenWord + " " + oddWord);
        }
        
    }
}
