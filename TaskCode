# oasist2
import java.util.*;
class Task2
{ static String phone,password;
	static int amount=50000;
	static Scanner s=new Scanner(System.in);
	static void register()
	{ System.out.println("enter your phone number");
    	phone=s.next();
		System.out.println("enter your password");
	  password=s.next();
	  System.out.println("Registered Successfully");
	  pass();
	}
	
	static void pass()
	{ try{
		String pin;
	System.out.println("enter your pin");
	 pin=s.next();
	 int i;
	 while(true)
	 {
	 if(pin.equals(password))
	 {System.out.println("******TRANSACTIONS AVAILABLE*******");
		 System.out.println(" 1.check balance\n 2.withdraw amount\n 3.deposit amount\n 4.Transfer amount\n 5.exit\nSELECT YOUR CHOICE");
      int k=s.nextInt();
	  switch(k)
	  {case 1:
		check();
		break;
	case 2:
		System.out.println("enter the amount to withdraw");
		int q=s.nextInt();
		withdraw(q);
		break;
	case 3:
		System.out.println("enter the amount to deposit");
		int w=s.nextInt();
		deposit(w);
		break;
	case 4:
		transfer();
		break;
	case 5:
		return;
	default :
		System.out.println("Invalid cloice");
	  }
	 }
	 else{
		 System.out.println("Incorrect pin");
		 pass();
	 }
	 System.out.println("");
	}}
	catch (Exception e)
	{}
	 }
	 
	
	static void check()
	{System.out.println("TOTAL BALANCE : "+amount);
	}
	
	static void withdraw(int y)
	{ if(y>amount)
		{System.out.println("Insufficient Funds");
	     return;
		}
	else
	{ amount-=y;
      System.out.println("Available Balance : "+amount);
	}}
	
	static void deposit(int y)
	{amount+=y;
	 System.out.println("Total Balance amount : "+amount);
	}
	
	static void transfer()
	 {System.out.println("enter the receiver's account number");
	  String e=s.next();
	  System.out.println("enter the amount");
	  int u=s.nextInt();
      if(u>amount)
		  System.out.println(" Insufficient Funds");
	  else{
		  amount-=u;
		  System.out.println("Available Balance : "+amount);
	 }}
	
	public static void main(String args[])
	{
		try {
			System.out.println("********WELCOME TO UK BANK ATM**********");
	System.out.println("1.Register\n2.enter the pin");
	int r=s.nextInt();
	String ph,p;
	switch(r)
	{
		case 1:
	    register();
		break;
	case 2:
	    pass();
		break;
	default:
	    System.out.println("Invalid choice");
		
		}}
		catch( Exception e)
		{}
}}
