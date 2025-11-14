#include<iostream>
using namespace std;
int main()
{
	int n;
	long long sum = 0;
	cout << "plz enter positive number" << endl;
	cin >> n;
	while (n < 0)
	{
		cout << "plz enter a positive number" << endl;
		cin >> n;
	}
	if (n > 0)
	{
		for (int i = 0; i <= n; i = i + 2)
		{
			sum = sum + i;
		}
	}
	cout << "The sum of all even number between 1 and n is:" << sum;
	return 0;
}
