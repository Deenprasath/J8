import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
		Scanner sc = new Scanner (System.in);
		int num = sc.nextInt();
		System.out.println("Enter the number");
	 	System.out.println(+num);
   
		if(num>0)
		{
		    System.out.println(num+ "positive");
		}
		else if(num<0)
		{
		    System.out.println(num+"negative");
		}
		else 
		{
		    System.out.println(num+"no value");
		}
		
		
}
}
