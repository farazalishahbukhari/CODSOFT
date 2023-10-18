# CODSOFT
Number Guessing
import java.util.scanner
import java.util.random

public class numberguessing {

public static void main (String []args){

Random rand= new random();
int numbertoguess=rand.nextInt(100);
int numberoftries=0;
Scanner input= new scanner(system.in);
int guess;
system.out.println("Guess the number ");
guess=input.nextInt();
numberoftries++;

if (guess==numbertoguess){
system.out.println("your guess is correct");
}

else (guess<numbertoguess) {
system.out.println("your number is low");
}
if else (guess>numbertoguess){
system.out.println("Your number is high);
} 

 }
}
