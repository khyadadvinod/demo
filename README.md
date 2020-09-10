class newvalue{
	int x,y;
	void init()
	{
		x=10;
		y=20;
	}
	void display() {
		System.out.println("x="+x);
		System.out.println("y="+y);
	}
}

public class newvalue1 {

	public static void main(String[] args) {
		newvalue p1 = new newvalue();
		p1.init();
		p1.display();

	}

}
