# PatternInJava
import java.util.Scanner;

public class Main
{
	public static void main(String[] args)
	{
	    Scanner sc = new Scanner(System.in);
	    System.out.print("Enter a number : ");
	    int z = sc.nextInt();
	    for(int i=1;i<=z;i++){
	        for(int j=1;j<=i;j++){
	            System.out.print("*");
	        }
	        System.out.println();
	    }
	}
}
