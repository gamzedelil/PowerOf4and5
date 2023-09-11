# PowerOf4and5

package poweroftwo;

import java.util.Scanner;

public class main {

	public static void main(String[] args) {
		
		Scanner input = new Scanner(System.in);
		
		int n;
		System.out.println("Choose the limit value:");
		n = input.nextInt();
		
		System.out.println("Powers of 4:");
		for (int i=1 ; i < n ; i *= 4) {
		System.out.println(i); }
		
		System.out.println("Powers of 5:");
        for (int i=1; i <= n; i *= 5) {
		System.out.println(i); 
		}
	}
}
