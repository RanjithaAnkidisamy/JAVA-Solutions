import java.util.*;
public class Hello {

    public static void main(String[] args) {
		//Your Code Here
		Scanner sc=new Scanner(System.in);
		String s=sc.nextLine();
		char[] s1=s.toCharArray();
		char ch='a';
		int n=s.length(),f=0;
		String sam1="",sam2="";
		for(int i=0;i<n;i++)
		{
		  
		    if(Character.isLetter(s1[i]))
		    {
		        ch=s1[i];
		         f=i;
		        break;
		    }
		    sam1=sam1+s1[i];
		}
		
		for(int j=f+1;j<n;j++)
		{
		    sam2=sam2+s1[j];
		}
    
    int a=Integer.parseInt(sam1);
		int b=Integer.parseInt(sam2);
		if(ch=='a' || ch=='A')
		{
		    System.out.print(a+b);
		}
		else if(ch=='s' || ch=='S')
		{
		    System.out.print(a-b);
		}
		else if(ch=='M' ||  ch=='m')
		{
		    System.out.print(a*b);
		}
		else if(ch=='D' || ch=='d')
		{
		    System.out.print(a/b);
		}
		

	}
}
