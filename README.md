# juspay
import java.util.Scanner;

public class Juspay {
	public static void main(String[] args) {
		Scanner a=new Scanner(System.in);
	System.out.println("enter the string");
	String x=a.next();
	StringBuffer s=new StringBuffer(x);
	s.reverse();
	StringBuffer q=new StringBuffer(" ");
	for(int i=0;i<s.length();i++)
	{
		q.append(s.charAt(i));
		q.append('-');
	}
	
System.out.println(q);
}
}
