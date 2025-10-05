# gjvgv
import java.util.Scanner;

class Student
{
	Student(int h)
	{
		float area=((float)Math.pow(3,0.5)* h)/4 ;
		System.out.println("  area: " +area);
	}
	Student(int h,int w)
	{
int area;
area=h*w;
		System.out.println("  area: " +area);
	}

	Student(float r)
	{
		double area=3.1416*r*r;
		System.out.println("  area: " +area);
	}
}
class Main {

public static void main(String[] args)
{
	Scanner in=new Scanner(System.in);
	
	System.out.print("enter height: ");
	int height=in.nextInt();
	System.out.print("enter height: ");
	int wight=in.nextInt();

	Student s1=new Student(height);
	Student s2=new Student(height,wight);
	Student s3=new Student(height);
//  	s1.Student(height);
//  	//s1.Student(height,wight);
//  	s1.Student(height);


}
}
