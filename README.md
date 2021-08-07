Question 1: What is the time complexity T(n) for the following code snippet?
a=1;
b=1;
while (b<=n){
a+=1;
b+=1;
cout<<"Hi";
}

Answer:- 

In a give code,we have assign two variables a and b equal to 1. And running the while loop till b gets equal to or less than 1.
Hence the given while loop will run for n times since increment in b is equal to 1.
So if my n=6 then loop will also run for 6 times and each time of loop execution the variable b is incremented by 1.

b=1-->b=2-->b=3-->b=4-->b=5-->b=6-->b=7 As b==7 condition meet it makes the statement b<=6 wrong and the loop terminates.

hence the loop will surely executes n times so time complexity is T(n)=O(n) since it depends on the input size i.e. n;


Question 2: Write the output for the following recursive code snippet for n=3:

void fun(int n)
{
  if (n>0){
   cout<<n;
   fun(n-1);
   cout<<n;
  }
}

Answer:- the output will be if n=5 then

54321
12345
