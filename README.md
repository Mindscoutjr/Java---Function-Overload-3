import java.lang.Math;

import java.util.Scanner;

public class Main

{

    public static double mathMethod(double x, double y)
    
    {
    
        return x + y;
        
    }
    
    public static int mathMethod(int x, int y)
    
    {
    
        return x*y;
        
    }
    
    public static void main(String[] args)
    
    {
    
        Scanner  mathes=new Scanner(System.in);
        
		System.out.println("Enter a number");
    
		int num = mathes.nextInt();
    
		mathes.close();
    
		System.out.println("Enter another number ");
    
		int num2 = mathes.nextInt();
    
		mathes.close();
    
		System.out.println("Your Sum is" + );
    
    }
    
        //How do you call the functions(mathMethod : x+y, x*y) inside the print statement?
        
}
