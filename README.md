#include<iostream>
using namespace std;

int main() {
	int n;
    cin>>n;
	int SO=0;
    int SE=0;
    int rem;
    while(n>0)
    {
    	rem=n%10;
        if(rem%2==0)
        {
            SE=SE+rem;
        }
        else
        {
            SO=SO+rem;
        }
        n=n/10;
    }
    cout<<SE<<" "<<SO; 
	
}
