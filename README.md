import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
        Scanner s=new Scanner(System.in);
        int n=s.nextInt();
        int[]a=new int[n];
        int[]b=new int[n];
        for(int i=0;i<n;i++){
            a[i]=s.nextInt();
            b[i]=s.nextInt();
            if(i%2==0){
                System.out.println(a[i] +b[i]);
            }
            else{
                System.out.println(a[i]*b[i]);
            }
        }
    }
}
