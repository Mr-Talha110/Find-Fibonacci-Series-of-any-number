//C++ code to find Fibonacci series of a number.


#include <iostream>
using namespace std;
int main(){
	int N;
	cout<<"Enter a number=";
	cin>>N;
	if(N==0){
		cout<<"Error";
	}
	else{
		
	
	int a=0, b=1, c=0;
	cout<<a<<"\t";
	cout<<b<<"\t";
	for(int i=1; i<=N; i++)
	{
		
		c=a+b;
		a=b;
		b=c;
		cout<<c<<"\t";
	}
}
	
}
