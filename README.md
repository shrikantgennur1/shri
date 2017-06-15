package training;

public class Constructor
{
	int x;
	int y;
	
	Constructor()
	{
		int x=20;
		int y=30;
		System.out.println("running defult constructor");
		 System.out.println("x  value is "+x);
		 System.out.println("y  value is "+y);
	}
	 
	
	
	 Constructor(int i, int j) 
	 {
		 this.x=i;
		 this.y=j;
		 
	}
	 void disp()
	 {
		 System.out.println("running parametric constructor");
		 System.out.println("i  value is "+x);
		 System.out.println("j value is "+y); 
	 }

	 public static void main(String[] args)
	 {
		 Constructor c1=new Constructor(); 
		 Constructor c=new Constructor(100,200);
		 c.disp();
		
	}

}
