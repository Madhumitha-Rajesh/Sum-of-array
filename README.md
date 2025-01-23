# Sum-of-array

Coding-

package sumofarray;

public class Sumofarray {
    public static void main(String[] args) {
        //sum of one-dimensional array
        int[] numbers={1,2,3,4,5};
        int sum=0;
        for(int num:numbers){
            sum+=num;
        }
        System.out.println("Sum of elements:"+sum);  
    }
}


Output-

run:
Sum of elements:15
