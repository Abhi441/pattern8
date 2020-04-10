# pattern8
import java.util.Scanner;
class Main {
public static void main (String[] args) {
    Scanner sc = new Scanner(System.in);
    int n = sc.nextInt();

    //row
    int row = 1;
    while( row<= n)
    {
      // work
      int col = 1;
      while( col <= n){
        if (row== col || row + col == n+1)
        {
          System.out.print("*");
        }
        else{
         System.out.print(" ");
        }
        col = col +1;
      }
        System.out.println();
        row = row + 1;
        
      }
         
    }
}
