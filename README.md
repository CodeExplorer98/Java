package Ex1;
 
import java.util.Scanner;

 public class Percentage {
        public static void main(String []args) {
        	System.out.println("RESULT");
        	System.out.println("Enter the marks gain in each subject: ");
        	System.out.print("1.D.S. :");
        	Scanner sc =new Scanner(System.in);
        	float a=sc.nextFloat();
        	System.out.print("2.Java:");
        	float b=sc.nextFloat();
        	System.out.print("3. MDM:");
        	float c=sc.nextFloat();
        	System.out.print("4. OE:");
        	float d=sc.nextFloat();
        	System.out.print("5. EVS:");
        	float e=sc.nextFloat();
        	System.out.print("6. Eco:");
        	float f=sc.nextFloat();
        	float total=a+b+c+d+e+f;
        	System.out.println("Total marks gained:"+total);
        	float per=(total/450)*10; 
        	System.out.println("CGP is:"+per);
       sc.close(); 	
        	
        }
	
	}



	
