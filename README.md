import java.util.*;
public class calculator {

	public static void main(String[] args)
	{
		char operator;
		int  num1, num2, result;
		
		 Scanner s =new Scanner(System.in);
		 System.out.println ("choose an operator:" +"'+'or"+"'-' or"+"'*' or"+"'/'");
		 operator =s. next().charAt(0);
		 
		 System.out.println("enter the First num:");
		 num1= s.nextInt();
		 System.out.println("enter the Second num:");
		 num2= s.nextInt();
		 System.out.println("the result are:");
		  
		 switch(operator)
		 {
		 case '+':
		 result =num1+num2;
		 
		 System.out.println(num1+"+"+num2+"="+result);
		 break;
		 case '-':
		 result =num1-num2;
		 System.out.println(num1+"-"+num2+"="+result);
		 break;
		 case '*':
		 result =num1*num2;
		 System.out.println(num1+"*"+num2+"="+result);
		 break;
		 case '/':
		 result =num1/num2;
		 System.out.println(num1+"/"+num2+"="+result);
		 break;
		 }
	}

}
