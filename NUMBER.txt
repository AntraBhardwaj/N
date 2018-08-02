package number;
import java.util.*;
public class Checknumb {

	public static void main(String[] args) 
	{
		// TODO Auto-generated method stub
        int a1;
        Scanner a = new Scanner(System.in);
         a1 = a.nextInt();
         a.close();
        if(a1%2==0)
        {
        	System.out.println("even");
        }
        else
        {
        	System.out.println("odd");
        }
	}

}
