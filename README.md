import java.util.Scanner;
public class rainbow {

	public static void main(String[] args) {
		Scanner input = new Scanner(System.in);
		System.out.println("Enter the first letter");
		char t1 = input.next().charAt(0);
		System.out.println("Enter the second letter");
		char t2 = input.next().charAt(0);
		System.out.println("Enter the third letter");
		char t3 = input.next().charAt(0);
		System.out.println("Enter the fourth letter");
		char t4 = input.next().charAt(0);
		System.out.println("Enter the fifth letter");
		char t5 = input.next().charAt(0);
		System.out.println("Enter the sixth letter");
		char t6 = input.next().charAt(0);
		System.out.println("Enter the seventh letter");
		char t7 = input.next().charAt(0);
		
		
		if ((t1 == 'R'||t1=='r') && (t2 == 'A'||t2=='a') && (t3 == 'I'||t3=='i') && (t4 == 'N'||t4=='n') && (t5 == 'B'||t5=='b') && (t6 == 'O'||t6=='o') && (t7 == 'W'||t7=='w') )
		{
			System.out.println("RAINBOW");
		}
		else
		{
			System.out.println("The spelling is wrong");
		}
		

	}

}
