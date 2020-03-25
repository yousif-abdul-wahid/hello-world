//Yousif Abdul Wahid
//Douglas Brewer
//Fernando Coronado (STAYING??????) y || n = 
//-
//-
//-

import java.util.Scanner;
public class greatestCommonDivisor {
   public static void main (String[] args) {
    Scanner scnr = new Scanner(System.in);    	
    int firstNum = 19;
    int secondNum;
    int greatestCommonDivisor = 1;
	boolean doesTheUserWantToContinue = true;
	char doesTheUserWantToContinueChar = ' ';
	while (doesTheUserWantToContinue){
		System.out.println("Please enter your first number: ");
		firstNum = scnr.nextInt();
System.out.println("Please enter your second number: ");
		secondNum = scnr.nextInt();
		greatestCommonDivisor = findGreatestDivisor(firstNum, secondNum);
		System.out.print("Here is the greatest common divisor: ");
		System.out.println(greatestCommonDivisor);
System.out.println("Do you want to enter 2 more numbers? Pick y for yes and n for no");
		doesTheUserWantToContinueChar = scnr.next().charAt(0);
		if (doesTheUserWantToContinueChar == 'y'){
			doesTheUserWantToContinue = true;
		}
		else{
			doesTheUserWantToContinue = false;
		}
}
}

public static int findGreatestDivisor(int userNumber1, int userNumber2 ){
	int whichIsSmaller, whichIsLarger, greatestCommonDivisor = 1;
	int isThereARemainder;
		if (userNumber1 <= userNumber2){
			whichIsSmaller = userNumber1;
			whichIsLarger = userNumber2;
		}
		else{ 
whichIsSmaller = userNumber2;
whichIsLarger = userNumber1;
}
			
	for ( int i = whichIsSmaller ; i >= 1; --i){
		isThereARemainder = whichIsLarger % i;
		if (isThereARemainder == 0){
			if ((whichIsSmaller % i) == 0 ) {
			greatestCommonDivisor = i;
			break;
			}
		}
	}
	return greatestCommonDivisor;
}
}
