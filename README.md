# Way-to-long-words-problem
#include<iostream>
using namespace std;

int main()
{
	int n;
	cin>>n;
	string str;
	while(n--)
	{
		cin>>str;
		if(str.length()>10)
		{
			cout<<str[0]<<str.length()-2<<str[str.length()-1]<<endl;
		}
		else
		cout<<str<<endl;
	}
	return 0;
}
