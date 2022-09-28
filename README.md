# part-6_Practical_4

package part6;

public class Prcatical_4 extends Thread{
	
	    public void run() {

	    }

	    public static void main(String[] args) {
	    	Prcatical_4  FIRST = new Prcatical_4 ();
	    	Prcatical_4  SECOND = new Prcatical_4 ();
	    	Prcatical_4  THIRD = new Prcatical_4 ();

	        FIRST.setPriority(3);
	        SECOND.setPriority(5);
	        THIRD.setPriority(7);

	        System.out.println("Priority of FIRST Thread:" + FIRST.getPriority());
	        System.out.println("Priority of SECOND Thread:" + SECOND.getPriority());
	        System.out.println("Priority of THIRD Thread:" + THIRD.getPriority());
	        System.out.println("This is created by 21CE063_Manav Luhar.");


	    }
	}

