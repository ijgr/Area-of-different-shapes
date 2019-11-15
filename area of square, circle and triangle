// area of square, circle and triangle
#include <iostream>
#include <string>
#include <cmath>
#define P 3.14
using namespace std;

int main()
{
	int shape;
	double area, area1;
	int base = 0;
	int radius = 0;
	int height = 0;
	int side = 0;
	cout << "What shape do you want to calculate the area: square(1), circle(2), triangle(3)" << endl;
	cin >> shape;
	area = (base*height) / 2;
	
	switch (shape)
	{
	case 1: cout << "Enter the side: ";
		cin >> side;
		cout << "The area is: " << side * side << endl;
		break;
	case 2: cout << "Enter the base: ";
		cin >> base;
		cout << "Enter height: ";
		cin >> height;
		cout << "The area is: " << ((base*height) / 2) << endl;
		break;
	case 3: cout << "Enter radius: ";
		cin >> radius;
		area1 = P * (pow(radius, 2));
		cout << "The area is: " << area1 << endl;
		break;
	}
	system("pause");
}
