package ArrayConcept;

import java.util.Arrays;
import java.util.List;

import com.mongodb.client.model.Sorts;

public class BasicArray {
	
	 public static void main(String[] args) {
		 
	   int num[]= new int[5];
	   num[0]= 20;
	   num[1]= 30;
	   num[2]= 200;
	   num[3]= 300;
	   num[0]=56;
	  
	  List<int[]> d= Arrays.asList(num);
	  int[] unsorted = {6, 5, 3, 1, 8, 7, 2, 4};
	  
	  
	  // System.out.println(num[0]);
	   int t= num.length;
	  // System.out.println(t);
	   
	   /* for(int p=0;p<t;p++) {                     
		  
		  System.out.println(num[p]);
	  }
	  */
	   
	   for(int l:num) {
		 //  System.out.println(l);
	   }
	 }
	 }
