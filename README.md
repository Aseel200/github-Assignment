#include <iostream>
using namespace std;
int main()
{
	double num1, num2, quotient;
	cout << "enter a number:";
	cin >> num1;

	cout << "enter another number:";
	cin >> num2;

	if (num2 == 0)
	{
		cout << "division by zero is not possible.\n";
		cout << "please run the program again and enter.\n";
		cout << "a number other than zero.\n";
	}
	else
	{
		quotient = num1 / num2;
		cout << "the quotient of" << num1 << "divided by ";
		cout << num2 << "is" << quotient << endl;

	}
	return 0;
}

