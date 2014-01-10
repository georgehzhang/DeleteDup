/************************************************************************************
Program Name:	Delete Duplicate / Delete Second to Last Duplicate 
Author:			George Zhang
************************************************************************************/

#include "Header.h"
#include <iostream>

using namespace std;

int main() {

	chain a;
	bool flag;


	/*Unsorted list*/
	a.insert(1, 0, flag);
	a.insert(1, 1, flag);
	a.insert(2, 2, flag);
	a.insert(2, 3, flag);
	a.insert(3, 4, flag);
	a.insert(3, 5, flag);
	a.insert(4, 6, flag);
	a.insert(4, 7, flag);
	a.insert(4, 8, flag);
	a.insert(4, 9, flag);
	a.insert(5, 10, flag);
	a.insert(4, 11, flag);
	a.insert(4, 12, flag);
	a.insert(5, 13, flag);
	a.insert(3, 14, flag); 
	a.insert(5, 15, flag);
	a.insert(3, 16, flag);


	cout << "Original List :" << endl;
	a.printAll();
	a.deleteLastDuplicate();
	cout << "New List: " << endl;
	a.deleteSecondLastDuplicate();
	/*Print linked list*/
	a.printAll();


	return 0;
}
