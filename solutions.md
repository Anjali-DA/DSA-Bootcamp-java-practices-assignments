**1.** Calculate electricity bill
``` Java
import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
		
		while(true){
		    Scanner input= new Scanner(System.in);
		    System.out.print("Enter watts of the appliances(in W): ");
		    float watts= input.nextFloat();
		    System.out.print("Enter the usage of the appliances: ");
		    float usage= input.nextInt();
		    System.out.print("Enter the electrcity rate(Can be differ country by country): ");
		    float e_rate= input.nextFloat();
		    
		    float kwh= (watts)*(usage*30)/1000;
		    float cost= kwh*e_rate;
		    System.out.println("Electrcity bill per month: " + cost);
		}
		
		
		
	}
}
```
