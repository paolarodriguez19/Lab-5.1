# Lab-5.1
Class: Introduction to Algorithms and Applications (COMP111) - Laboratory #5.1 -Yards in C++

#include <iostream>

using namespace std;

void main() {
 
 float yards = 0; 
 float feet = 0; 
 float inches = 0;
 
 cout << "Welcome to the Yards Calculator" << endl;
 
 cout << "Enter the number of Yards: ";
 cin >> yards;
 
 feet = yards * 3;
 
 inches = yards * 36;
 
 cout << "yards : " << yards << endl;
 cout << "feet : " << feet << endl;
 cout << "inches: " << inches << endl;
 
 system("pause"); 
}
