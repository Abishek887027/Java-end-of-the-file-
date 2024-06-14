import java.io.*;
import java.util.*;
import java.text.*;
import java.math.*;
import java.util.regex.*;

public class Solution {
    public static void main(String[] args) {
        
        int i=1;
        Scanner sc= new Scanner(System.in);
        while(sc.hasNext()){
            String currentStr=sc.nextLine();
            System.out.println(i+" "+currentStr);
            i++;
        }
     sc.close();  
    }
}
