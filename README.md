# HARSHARD-NUMBER
Write a C program to find whether the given number is Harshard number or not.

Sample Input:
1729

Sample Output:
Harshard number

ANSWER:
#include<iostream>
using namespace std;
int main()
{
     int n,a,b;
     int sum=0;
     cin>>n;
     b=n;
     while(n!=0)
     {
         a=n%10;
         n=n/10;
         sum=sum+a;
     }
     if(a%sum==0)
     {
         cout<<"Harshard number";
     }
     else
     {
         cout<<"Not Harshard number";
     }
        return 0;
}
