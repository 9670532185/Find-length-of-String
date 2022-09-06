# Find-length-of-String
#include<iostream>
using namespace std;
int Length(char name[])
{
	int c=0;
	for(int i=0;name[i] !='\0';i++)
	{
		c++;
	}
	return c;
}
int main()
{
	char name[20];
	cin>>name;
	cout<<name<<endl;
	cout<<"Length of name is"<<endl;
	cout<<Length(name);
}

