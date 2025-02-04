Check if two arrays are the same or not
Here we want to check whether two arrays are the same or not. The two arrays are the same when their length is equal.

so for checking that both arrays are same or not, we need to calculate the length of both array and then check the length is same or not.

Two arrays are said to be equal if both of them contain the same set of elements, arguments of elements though.

here we sort the array because it makes a comparison essay.

now we will discuss the working of the program and also discuss the program of this.

Equal array
Working
Step 1. Initialize two arrays.

Step 2. Declare the scanner class for taking input.

Step 3. take array size for both arrays from the user.

Step 4. Take an element of both array from the user.

Step 5. Check that equal function return true or false

Step 6. If true then both arrays are same otherwise arrays ara not same

equal(int a1[], int a2[])

Step 1. Find the length of both array

Step 2. If the length of both arrays is not equal then return false.

Step 3.  Sort both arrays.

Step 4. Initialise the for loop from 0 to length for check the element is same or not.

Step 5. If any element of the array is not equal to another array so return false.

Step 6. Return true.

C	JAVA	Python 1	Python 2

import java.util.*;

public class Pavan
{
public static void main(String[] args)
{
int a[]={1,2,3,4};
int b[]={4,2,1,3};
Arrays.sort(a);
Arrays.sort(b);
if(Arrays.equals(a,b))
{
System.out.println(“both arrays are same”);
}
else
{
System.out.println(“not Same”);
}
}
}

Output
enter size of array 1                                                                                                        
4                                                                                                                            
enter element                                                                                                                
2                                                                                                                            
4                                                                                                                            
13                                                                                                                           
1                                                                                                                            
enter size of array2                                                                                                         
4                                                                                                                            
enter element                                                                                                                
4                                                                                                                            
2                                                                                                                            
1                                                                                                                            
13                                                                                                                           
Both array is same 
