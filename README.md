# prep2

// program to find hypotenuse of a triangle
package my_first_java_Project;
import java.util.Scanner;

public class main {

	public static void main(String[] args) {
		double x;
		double y;
		double z;
		Scanner sc=new Scanner(System.in);
		System.out.println("enetr side x:");
		x=sc.nextDouble();	
		System.out.println("enetr side y:");
		y=sc.nextDouble();
		z=Math.sqrt(x*x+y*y);
		System.out.println("THE HYPOTENUESE IS "+z);
		
		
	} 

} 

// program to define the use of random 
package my_first_java_Project;
import java.util.Random;

public class main {

	public static void main(String[] args) {
		Random random=new Random();
		int x =random.nextInt(6);//limits the range of values
		System.out.println(x); 
		
		
	} 


 
package my_first_java_Project;
import java.util.Random;

public class main {

	public static void main(String[] args) {
		Random random=new Random();
		double x=random.nextDouble();// double random usage
		System.out.println(x); 
		
		
	} 

} 


package my_first_java_Project;
import java.util.Random;

public class main {

	public static void main(String[] args) {
		Random random=new Random();
		boolean x=random.nextBoolean();//getting random boolean valuee
		System.out.println(x); 
		
		
	} 

} 

//switch statement usage
package my_first_java_Project;
import java.util.Scanner;

public class main {

	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	System.out.println("enter the day");
	String day=sc.nextLine();
	switch(day) {
	
	case "monday":System.out.println("today is monday");
	break;
	case "tuesday":System.out.println("tuesday");
	break;
	case "wednesday":System.out.println("wednesday");
	break;
	case "thursday":System.out.println("thursday");
	break;
	case "friday":System.out.println("today is friday");
	break;
	case "saturday":System.out.println("saturday ");
	break;
	case "sunday":System.out.println("today is sunday");
	break;
	default:System.out.println("monday");
	}
		
} 

} 

//response equals
package my_first_java_Project;
import java.util.Scanner;

public class main {

	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	System.out.println("you are playing a game.if you want to quit prerss q or Q");
	String response=sc.next();
	if(response.equals("q")|| response.equals("Q"))
	{
	 System.out.println("you are out of your game ");
	}
	else {
	 System.out.println("you are still playing your game");
	 }
	}
}


} 
