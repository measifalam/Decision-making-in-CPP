# Decision-making-in-CPP
Decision making structures require that the programmer specify one or more conditions to be evaluated or tested by the program, along with a statement or statements to be executed if the condition is determined to be true, and optionally, other statements to be executed if the condition is determined to be false.

//1.Basic
~~~~~~~~~~~~~
#include<iostream>
  int main()
  {
    int j;
   for(j=1;j<1;j++)
   {
     cout<<" "<<j;
     return 0;
   }
                  
//2.Basic
~~~~~~~~~

#include<iostream>
int main()
{
  j=0;
  for(j<11;j++)
  {
   cout<<" "<<j;
   }
  return 0;
}

==================
//3.Basic
~~~~~~~~~
#include<iostream>
int main()
{
 int j=0;
 for(;j<11;)
 {
 cout<<" "<<j;
 ++j;
 }
 return 0;
 
 =======================
 
 //4.To display all leap year
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 
 #include<iostream>
  int main()
  {
   int i=1999;
   cout<<"\n Program to print all the leap years from 2000 to 2012";
  for(;i++<=2012;)
  {
    if(i%4==0 && i%100!=0)
        {
        cout<<i<<" ";
        }
    else if(i%100==0 && i%400==0)
        {
        cout<<i<<" ";
        }
     return 0;
   }
                  
 =================================
 
 //5.Demonstrate nested for lopps
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 
 #include<iostream>
 int main()
 {
   int a,b,c;
   for(a=1;a<=2;a++)
   {
   for(b=1;b<=2;b++)
   {
    for((c=1;c<=2;c++)
    {
      cout<<"\n a = "<< a <<" + b = "<< b <<" + c = "<<c<<":"<<a+b+c;
      cout<<"Inner loop over";
    }
    cout<<" Middle loop " ;
   }
   cout<<" Outer loop ";
 return 0;
 }
 
 ===============================
 
 //6. Add 10 consecutive no.
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~
 
 #include<iostream>
 int main()
 {
  int a=1,sum=0;
  while(a<=10)
  {
   cout<<" "<<a;
   sum=sum+a;
  a++;
  }
  
  cout<<"\n Sum of ten numbers:"<<sum;
  return 0;
  }
  
  ========================
  
  //7. calculate the sum of individual digits
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  
  #include<iostream>
  int main()
  {
   int num,t;
   cout<<"Enter number";
   cin>>num;
   int sum=0;
   while(num!=0)
   {
    sum=sum+num%10;
    num=num/10;
    }
  cout<<"\n Sum of the individual digits of the number="<<t<<sum;
  return 0;
  }
    
        
 }
   
                
  
