# TicTacToe
//a very basic c++ tictactoe game. (still needs a mechanism to check for a winner)

#include <iostream>
#include <string>
using namespace std;

int main(){
	char box1 = '.';
	char box2 = '.';
	char box3 = '.';
	char box4 = '.';
	char box5 = '.';
	char box6 = '.';
	char box7 = '.';
	char box8 = '.';
	char box9 = '.';
	int boxNumber;
	char xOrO;
	
	cout << "Ready to play TicTacToe!" << endl;
	
	cout << "  " << box1 << "  " << box2 << "  " << box3 << endl;
	cout << "  " << box4 << "  " << box5 << "  " << box6 << endl;
	cout << "  " << box7 << "  " << box8 << "  " << box9 << endl;

	cout << "Boxes are numbered with top left being 1 and bottom right being 9" << endl;	
	
	for (int i; i<10; i++){
		cout << "Select a box number ";
		cin >> boxNumber;
		cout << "Select 'x' or 'o'";
		cin >> xOrO;

		if(boxNumber==1)
			box1 = xOrO;
		else if(boxNumber==2)
                	box2 = xOrO;
		else if(boxNumber==3)
                	box3 = xOrO;
		else if(boxNumber==4)
                	box4 = xOrO;
		else if(boxNumber==5)
                	box5 = xOrO;
		else if(boxNumber==6)
                	box6 = xOrO;
		else if(boxNumber==7)
                	box7 = xOrO;
		else if(boxNumber==8)
                	box8 = xOrO;
		else if(boxNumber==9)
                	box9 = xOrO;
		else
			cout << "Invalid";

		cout << "  " << box1 << "  " << box2 << "  " << box3 << endl;
        	cout << "  " << box4 << "  " << box5 << "  " << box6 << endl;
        	cout << "  " << box7 << "  " << box8 << "  " << box9 << endl;

	}
	return 0;
}
