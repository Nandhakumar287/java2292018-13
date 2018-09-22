import java.io.*;
import java.util.*;
  public class NumOddOrEven{
    public static void main(String args[]){
      Scanner sc=new Scanner(System.in);
      System.out.println("Enter Two Numbers");
      int a=sc.nextInt();
      int b=sc.nextInt();
      if((a+b)%2==0)
      {
      System.out.println("Even");
      }
      else{
      System.out.println("Odd");
      }
    }
   } 
