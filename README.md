# Array-matrix
Array with randam number

package D2_array;
import java.util.*;

public class user_input {
	public static void main(String[]args) {
		int a[][];
		a= new int [2][2];
		
		int b[][];
		b= new int [2][2];
		int sum[][];
		sum= new int [2][2];
		
		for(int i=0;i<a.length;i++) {
			
			for(int j=0;j<a[i].length;j++) {
				a[i][j]=(int)(Math.random()*1000);
			}
			
		}
		
		for(int i=0;i<b.length;i++) {
			
			for(int j=0;j<b[i].length;j++) {
				b[i][j]=(int)(Math.random()*100);
			}
			
		}
		
		System.out.println("print firsh array");
		
		for(int i=0;i<a.length;i++) {
			
			for(int j=0;j<a[i].length;j++) {
				System.out.print(a[i][j]+" ");
			}
			System.out.println();
		}
		System.out.println("print second array");
			for(int i=0;i<b.length;i++) {
			
			for(int j=0;j<b[i].length;j++) {
				System.out.print(b[i][j]+" ");
			}
			System.out.println();
		}
			
			System.out.println("sum of the array");
			
			
			for(int i=0;i<sum.length;i++) {
				
				for(int j=0;j<sum[i].length;j++) {
					sum[i][j]=a[i][j]+b[i][j];
				}
				
			}
			
			for(int i=0;i<sum.length;i++) {
				
				for(int j=0;j<sum[i].length;j++) {
					System.out.print(sum[i][j]+" ");
				}
				System.out.println();
			}
		
		
	}

}
