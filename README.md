# prework_3
import java.util.Scanner;
class PatternPrinter {
 public static void main(String[] args) {
 Scanner in = new Scanner(System.in);
 int n = in .nextInt();
 patternPrinter(n);
 }
 static void patternPrinter(int n) {
    int m = n;
    int c = n;
    while(m>0){
        for(int j = n; j > 0 ; j--){
            int c = n;
            int k = j;
            while(c>0){
                System.out.print(k); 
                c--;
            }
        }
        System.out.println();
        m--;
    } 
   
 }
}
