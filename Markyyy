#include <iostream>
#include <direct.h>
#include <dos.h>

using namespace std;

void list_file();
void directory();
void change_dir();

int main() {
	
	int choice;
	
	cout << "      Main Menu     " << endl;
	cout << "_ _ _ _ _ _ _ _ _ _ _ _ _ _"<< endl;
	
	cout << "1. To Display List of files\n";
	cout << "2. To Create New Directory\n";
	cout << "3. To Change the Working Directory\n";
	cout << "4. Exit\n";
    cout << "Enter The Number: ";
	cin >> choice;			
	
	switch (choice) {
		case 1:
			list_file();
			break;
		case 2:
			directory();
			break;
		case 3:
			change_dir();
			break;
		deafault:
			break;
			
	}
	
}

void list_file() {
	
	int choice;
	
	cout <<"     LIST FILE DETAIL     \n";
	cout <<"_ _ _ _ _ _ _ _ _ _ _ _ _ _\n";
	cout <<"1. List All Files\n";
	cout <<"2. List of Extension Files\n";
	cout <<"3. List of Name Wise\n";
	cout <<"Enter the Number: ";
	cin  >>choice;
	
	
	
	switch (choice) {
		case 1:
			cout <<"List of All Files" << endl;
			
	    case 2:
	    	cout <<"file1.txt" << endl;
	    	
	    case 3:
		    cout <<"file2.cpp" << endl;
			
		case 4:
		    cout <<"report.doc" << endl;
			
		case 5: 
		    cout <<"image.jpg" << endl;
							
	}
}

void directory() {
	cout << " Enter the Directory name: Newfolder  " << endl;
 cout << " Current Directory: C: | Users  | Username | Documents" << endl;
	cout << " NewFolder Directory Successfully Created " << endl;
	cout << " Press any key to continue.... ";
}

void change_dir() {
	
		int choice; 
		
	cout << "Current Directory: C:|Users|UserName|Documents" <<endl;
	cout << "Change Directory" <<endl;
	cout << "---------------------" <<endl;
	cout << "1. Step by Step Backward" <<endl;
	cout << "2. Goto Root Directory" <<endl;
	cout << "3. Forward Directory" <<endl;
	cout << "Enter the Number: " <<endl;
	cin  >> choice; 
	
	
	cout << "Please enter the Directory Name: Projects" <<endl;
	cout << "Current Directory: C:|Users|Username|Documents|Projects" <<endl;
	cout << "Press any key to continue...";
}
