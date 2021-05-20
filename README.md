public class Jala {
	int id=10;
	static String name ="Sai";
	int ht=5;
	static void getname()
	{
		System.out.println(name);
	}
	void getid()
	{
		System.out.println(id);
	}
	public static void main(String[] args) {
		Jala j = new Jala();
		getname();
		j.getid();
	}
}
