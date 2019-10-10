#include "stdafx.h"
#include <iostream>
#include <cstdlib>

using namespace std;

int main()
{
	int nk;
	long long suma = 1;

	cout << "podaj liczbe" << endl;
	cin >> nk;

	for (int i = 1; i <= nk; i++)
		suma *= i;

	cout << suma << endl;

	system("PAUSE");
	return(0);
}
