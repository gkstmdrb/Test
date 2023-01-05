# Test
  package project;
import java.util.Scanner;
public class forgit {

	public static void main(String[] args) {
		
		String[] product = new String[3];
		product[0] = "watermelon";
		product[1] = "starwberry";
		product[2] = "orange";
		
		int[] price = {100, 200, 300};
		
		Scanner sc = new Scanner(System.in);
		String name;
		
		System.out.println(" 0\t\t 1\t\t  2");
		System.out.println("watermelon\tstarwberry\torange");
		
		System.out.print("enter your name: ");
		name = sc.next();
		
		System.out.print("choose fruit one: ");
		int fruit = sc.nextInt();
		
		System.out.print("pick a quantity: ");
		int per = sc.nextInt();
		
		System.out.println(name+"\n"+ product[fruit]+"\n"+(price[fruit] * per));
		
	}

}
