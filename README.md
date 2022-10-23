# Binary_overlading
A program to include all possible binary operator overloading using friend function.

#include<iostream>
#include<conio.h>
using namespace std;
class Distance
{
	public:
		int feet,inch;
		Distance()
		{
			this->feet=0;
			this->inch=0;
		}
		Distance(int f,int i)
		{
			this->feet=f;
			this->inch=i;
		}
		friend Distance operator+(Distance&, Distance&);
};
Distance operator+(Distance& d11,Distance& d22)
{


