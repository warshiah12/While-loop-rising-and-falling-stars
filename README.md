# While-loop-rising-and-falling-stars
#stars from 5 to 1 &amp; 1 to 5
#include<iostream>
using namespace std;
int main()
{
	int j, z = 1;
	j = 1;
	while (j <= 5)
	{
		z = j;
		while (z <= 5)
		{
			z++;
			cout << "*";
		}
		j++;
		cout << endl;
	}
	int s, k = 1;   
	s = 1;   
	while (s <= 5)   
	{
		k = 1;    
		while (k <= s)    
		{
			k++;
			cout << "*";
		}
		s++;
		cout << endl;
	}
	return 0;
}
