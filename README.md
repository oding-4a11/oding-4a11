#include<iostream>

using namespace std;



int main()

{

	int i,j,k,a=1;

	

	for(i=1;i<=4;i++)

	{

		for(k=4;k>=i;k--)

		{

			cout << " ";

		}

		for(j=1;j<=i;j++)

		{

			cout << a << " ";

			a++;

		}

		cout << "\n";

	}

	return 0;

}

