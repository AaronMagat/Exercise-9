# Exercise-9




#include <iostream>
using namespace std;

int main()
{
	
	double myNum=20;
	
	while (myNum>0) {
		myNum = myNum - 0.5;
		cout << myNum << endl;
	}
	
}
  
  
  
  
  
  #include <iostream>  
using namespace std;

int main() 
{

    int num=108;
    
    while (num>=9 )  //while conditional check
    {
        //code to output then decrease number
        cout << num << endl;
        num = num - 9;
              
    }

    cin.get(); //keeps console window open in Visual  Studio
    return 0;
}
  
  
  
  
  
  
  #include <iostream>
using namespace std;
int main()
{
	string password = "246";
	string userInput;
	int x = 5;
	cout << "You will only have 5 attempts" << endl;


	while (x > 0)
	{
		cout << "Enter the pass code for the safe" << endl;
		cin >> userInput;
		if (userInput == password)
		{
			cout << "You have finally unlocked the safe" << endl;

			break;
		}
		else
			x--;
	}
	//to print the ran out of message only if the password was not found within 5 attempts
	if (x == 0)
	{
		cout << "You ran out of attempts" << endl;
	}
}
  
  
  
  
  
  
  
  
  #include <iostream>
using namespace std;
int main() {

char input; 
do
{
	cout << "Would you like to Quit (Y/N)?" <<
		endl;
	cin >> input;
} 
while ((input != 'Y') && (input != 'y'));

return 0;
}
  
  
  
  
  #include <iostream>
using namespace std;
int main()
{
	string password = "246"; 
	string userInput;
	


	while (userInput != password)
	{
		cout << "Enter the pass code for the safe" << endl;
		cin >> userInput;

	}
	//to print the ran out of message only if the password was not found within 5 attempts
	cout << "You found the code";
}
  
  
  
  
  
  //if you don't want to end the loop no matter what

#include <iostream>
using namespace std;
int main()
{
    cout << "Enter a number either 1 or 2\n";
    string x;
    cin >> x;
    while (true)
    {
        if (x == "1")
        {
            cout << "you have entered the number 1\n";
            cout << "Enter a number either 1 or 2\n";
            cin >> x;
        }
        else if (x == "2" )
        {
            cout << "you have entered the number 2\n";
            cout << "Enter a number either 1 or 2\n";
            cin >> x;
        }
        else
        {
            cout << "you did not enter the number 1 and 2\n";
            cout << "Enter a number either 1 or 2\n";
            cin >> x;
        }
    }
}
  
  
  
  
  
  
  
  
  
  
  //To exit the loop if user enter anything other than one or two

#include <iostream>
using namespace std;
int main()
{
    cout << "Enter a number either 1 or 2\n";
    int x; 
    cin >> x;
    while (x != 0 && x <= 2 && !cin.fail())
    {
        if (x == 1)
        {
            cout << "you have entered the number 1\n";
        }
        else
        {
            cout << "you have entered the number 2\n";
        }

        cout << "Enter a number either 1 or 2\n";
        cin >> x;
     
    }
cout << "You did not enter the number 1 or 2";

}
  
  
  
  
  
  
  
  
  
  #include <iostream> 
using namespace std; 
int main() {

char input;  
do {
	cout << "Would you like to Quit (Y/N)?" << endl;
	cin >> input;
	
} 
while ((input != 'Y') && (input != 'y') );

return 0;
}
  
  
  
  
  
  #include <iostream>  
using namespace std; 
int main() {

	int myInt = 0, counter;
	cout << "Enter a number\n";
	cin >> counter;
	do
	{
		cout << myInt << endl;
		myInt++;

	} while (myInt<=counter);

}
