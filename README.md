# Oops-3-Assignments-1


public class Recarea
{
	class Dimensions
	{
	int length;
	int breadth;
	}

	class Rectangle extends Recarea
	{
	int a;
	public int length;
	public int breadth;
	void area()
	{
		a=length*breadth;
	}
	}

	class Area
	{
	public void main(String args[])
	{
	Rectangle Rect = new Rectangle();
	Rect.length = 7;
	Rect.breadth = 16;
	Rect.area();
	System.out.println("The Area of rectangle of length "
	+Rect.length+" and breadth "+Rect.breadth+" is "+Rect.a);
	}
	}
}
	
