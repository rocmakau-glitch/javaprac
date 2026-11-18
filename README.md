# javaprac
import java.util.Scanner;
public class FindMinimum {
    public static void main(String[] args)
    {
        Scanner input=new Scanner(System.in);
        int[]number=new int[5];
        System.out.println("Enter five numbers:");
        for(int i=0;i<5;i++)
        {
            number[i]=input.nextInt();
        }
        int min=number[0];
        for(int i=1;i<5;i++)
        {
            if(number[i]<min)
            {
                min=number[i];
            }
        }
        System.out.println("The minimum number is: " + min);
    }
}
