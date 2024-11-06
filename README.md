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

		
		
		
		
		
		
		
		// TODO Auto-generated method stub

	}

}
