package laptrinh;
import java.util.Scanner;
public class hello {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("--------------------------");
		System.out.println("hay nhap thong tin cau ban");
		System.out.println("--------------------------");
		System.out.println("nhap ho va ten: ");
		String hoten = sc.nextLine();
		System.out.println("nhap nam sinh: ");
		int namsinh = sc.nextInt();
		sc.nextLine();
		System.out.println("nhap ma lop: ");
		String malop = sc.nextLine();
		System.out.println("nhap ma so sinh vien: ");
		int MSSV = sc.nextInt();
		
		
		
		
		
		System.out.println("ho va ten la: "+ hoten);
		System.out.println("nam sinh la: "+ namsinh);
	    System.out.println("ma lop: "+ malop);
	    System.out.println("MSSV: "+ MSSV);
	   
	    int tong= 2024-namsinh;
	    System.out.println("vay nam nay tuoi ban la:  "+ tong);
	   
		
		
		
		// TODO Auto-generated method stub

	}

















package TEST1;
import java.util.Scanner;
public class bai1 {



	public static void main(String[] args) {
		
		Scanner sc = new Scanner(System.in);
		System.out.println("nhap vao a: ");
		int a = sc.nextInt();	
		System.out.println("nhap vao b: ");
		int b = sc.nextInt();
		System.out.println("nhap vao c: ");
		int c = sc.nextInt();

		if(a>b&&a>c)
		System.out.println("la so lon nhat: "+a);
		
		else if(b>a&&b>c)
		 System.out.println("la so lon nhat: "+b);
		
		else
		 System.out.println("la so lon nhat "+c);	
	
	
	    if( (a+b>c)&&(a+c>b)&&(b+c>a)){
	    	System.out.println("day la tam giac ");
	   
	    if(a==b&&b==c){
	    	System.out.println("day la tam giac deu ");
	    }else if(a==b||b==c||a==c){
	    	System.out.println("day la tam giac can");
	    } else{
	     System.out.println("day la tam giac thuong ");
	    }
	    }else{
	    	System.out.println("day khong phai tam giac ");
	    	
	    	
	    	
	    	
	    	
	    	
	    	
	    	
	    	
		
		
	    }
		
		
		
		
		// TODO Auto-generated method stub

	}

}












 

}
