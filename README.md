# CodSoft-task4

TASK 4: CURRENCY CONVERTER:
1.	Currency Selection: Allow the user to choose the base currency and the target currency.
2.	Currency Rates: Fetch real-time exchange rates from a reliable API.
3.	Amount Input: Take input from the user for the amount they want to convert.
4.	Currency Conversion: Convert the input amount from the base currency to the target currency using the fetched exchange rate.
5.	Display Result: Show the converted amount and the target currency symbol to the user.


Ans:


	import java.util.Scanner;
	class Currency
	{
    public static void main(String [] args)
    {
       int a;
       double UK=0.012,inr=83.38, b,sum,c,d;
       System.out.println("1.India to U.K");
       System.out.println("2.U.K to India");
       System.out.println("Choose your option");
       Scanner A=new Scanner(System.in);
       a=A.nextInt();
       if(a==1)
       {
         System.out.println("Enter Indian Currency:");
         c=A.nextDouble();
        sum=c*UK;
          System.out.println("U.K Currency:"+sum);
       
       }
       else if(a==2)
       {
          System.out.println("Enter U.K Currency:");
          b=A.nextDouble();
          sum=b*inr;
          System.out.println("Indian Currency:"+sum);
       }
       else
       {
         System.out.println("Choose correct option");
       }
    }
	}
Instraction:

 	1. Copy Full code.
 	2. Save: Currency.java
 	3. Compile: javac Currency.java
 	4. Run: java Currency
