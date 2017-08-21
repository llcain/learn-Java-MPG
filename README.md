# learn-Java-MPG


import java.util.Scanner;
public class App {

    public static void main(String args[]) {
        // initialize variables

        float drivenMiles;
        float gasGallons;
        float result;

        Scanner Keyboard = new Scanner(System.in);

        //get the number of miles driven

        System.out.println("How many miles have you driven?");
        drivenMiles = Keyboard.nextFloat();

        //get the number of gallons of gas used

        System.out.println("How many gallons of gas have been used?");
        gasGallons = Keyboard.nextFloat();

        //calculate the result of miles driven by number of gallons used

        result = drivenMiles / gasGallons;

        //Display calculation to screen

        System.out.println("Your car's MPG is " + result);



            }
        }
