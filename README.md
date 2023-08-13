import java.util.*;
public class ArraysCC{
public static void main(String args[]){
    int marks []=new int [10];
    Scanner sc =new Scanner(System.in);
    System.out.println("enter your math marks :");
    marks[0]=sc.nextInt();
    System.out.println("enter your phy marks :");
    marks[1]=sc.nextInt();
    System.out.println("enter your chy marks :");
    marks[2]=sc.nextInt();
    System.out.println("math marks :"+marks[0]);
    System.out.println("phy marks :"+marks[1]);
    System.out.println("chy marks :"+marks[2]);

    // update marks 
    marks[0]+=5;
    System.out.println("marks math :" +marks[0]);

    // total percentage 
    int percentage =(marks[0]+marks[1]+marks[3])/3;
    System.out.println("percentage = "+percentage);

}
}
