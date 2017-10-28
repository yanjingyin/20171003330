# 20171003330
//转换十进制数为二进制
#include <iostream>
using namespace std;
void din(int);
int main()
{
	int s,h;
	cout<<"请输入一个十进制整数：";
	cin>>s;
	cout<<"二进制数：";
	din (s);	 
	return 0;
}
void din(int n)     //递归函数
{
 	if (n == 0)
 	{
  		return;
 	}
 	else
 	{
  		din (n/2);
  		n=n%2;
  		cout<<n;
 	}
}
