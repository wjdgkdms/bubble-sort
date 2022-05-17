# bubble-sort
package jyt;
public class bubbleSort_0502 {
	public static void main(String[] args) {
		
	int[] 아무거나 = {18, 88, 7, 99, 3, 9999, 280, 1};
	
		for(int a=1; a<아무거나.length; a++) {
			// System.out.println(a+"번째");
			System.out.printf("%d번째 \n", a);
			for(int i=0; i<아무거나.length-1; i++) {
				if(아무거나[i]>아무거나[i+1]) {
					int temp = 아무거나[i];
					아무거나[i] = 아무거나[i+1];
					아무거나[i+1] = temp;	
					System.out.print("교환작업! ");
					for(int j=0; j<아무거나.length; j++) {
						System.out.print(아무거나[j]+" ");
					}
					System.out.println("");
				}
			}
		}
		
		
		for(int i=0; i<아무거나.length; i++) {
			System.out.print(아무거나[i]+" ");
		}
		
	}

}
