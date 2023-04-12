#include<iostream>
#include<cmath>
using namespace std;

double luaslingkaran(double r){
	double pi = M_PI;
	return pi*r*r;
}

int main(){
	double r;
	
	cin >> r;
	
	cout << "Luas Lingkaran: " << luaslingkaran(r);
	
	return 0;
}
