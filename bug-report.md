# Bug 1

1. **The incorrect original code or code snippit that you wrote:**

``` cpp
// assignment-4.cpp : This file contains the 'main' function. Program execution begins and ends there.

#include <iostream>
using namespace std
void printLargerElements(int* a, int size, int num);
//main function
int main()
{
	int a[50];
	int size;
	int num;
	//
	cout << "Enter the size of the array: ";
	cin >> size;
	cout << "Enter the elements into the array: ";
	
	
	cout << "Enter the elements into the array: " << endl;
	for (int i = 0; i < size; i++)
	{
		cout << "a[" << (i + 1) << "]: ";
		cin >> a[i];
		cout << endl;
	}
	
	cout << "The elements entered are: " << endl;
	for (int i = 0; i < size; i++)
	{
		cout << "[" << a[i] << "] ";
	}
	cout << endl;
	
	cout << "To print the array elements larger than the "
		<< "given number you need to enter a number." << endl;
	cout << "Enter a number: ";
	cin >> num;
	
	printLargerElements(a, size, num);
	system("pause");
	return 0;
}

void printLargerElements(int* a, int size, int num)
{
	cout << "Elements that are larger than the number " << num << " are: " << endl;
	for (int i = 0; i < size; i++)
	{
		if (a[i] > num)
			cout << "[" << a[i] << "] ";
	}
	cout << endl;
}

```

2. **What bug does the original code have?**

 the code does not have porper syntax

3. **What misunderstanding of C++ concepts lead you to this incorrect code?**
we should know the syntax of the application
4. **How to correct the bug?**
i checked and edited the syntax i did wrong.
5. **The corresponding bug-free code or code snippet is:**

```cpp
// assignment-4.cpp : This file contains the 'main' function. Program execution begins and ends there.

#include <iostream>
using namespace std;
void printLargerElements(int* a, int size, int num);
//main function
int main()
{
	int a[50];
	int size;
	int num;
	//
	cout << "Enter the size of the array: ";
	cin >> size;
	cout << "Enter the elements into the array: ";
	
	
	cout << "Enter the elements into the array: " << endl;
	for (int i = 0; i < size; i++)
	{
		cout << "a[" << (i + 1) << "]: ";
		cin >> a[i];
		cout << endl;
	}
	
	cout << "The elements entered are: " << endl;
	for (int i = 0; i < size; i++)
	{
		cout << "[" << a[i] << "] ";
	}
	cout << endl;
	
	cout << "To print the array elements larger than the "
		<< "given number you need to enter a number." << endl;
	cout << "Enter a number: ";
	cin >> num;
	
	printLargerElements(a, size, num);
	system("pause");
	retrn 0;
}

void printLargerElements(int* a, int size, int num)
{
	cout << "Elements that are larger than the number " << num << " are: " << endl;
	for (int i = 0; i < size; i++)
	{
		if (a[i] > num)
			cout << "[" << a[i] << "] ";
	}
	cout << endl;
}

```

6. **What is the take-away message from this bug?**

we must check the assignment after its done.

# Bug 2

1. **The incorrect original code or code snippit that you wrote:**

```
// assignment-4.cpp : This file contains the 'main' function. Program execution begins and ends there.

#include <iostream>
using namespace std;
void printLargerElements(int* a, int size, int num);
//main function
int main()
{
	int a[50];
	int size;
	
	cout << "Enter the size of the array: ";
	cin >> size;
	cout << "Enter the elements into the array: ";
	
	
	cout << "Enter the elements into the array: " << endl;
	for (int i = 0; i < size; i++)
	{
		cout << "a[" << (i + 1) << "]: ";
		cin >> a[i];
		cout << endl;
	}
	
	cout << "The elements entered are: " << endl;
	for (int i = 0; i < size; i++)
	{
		cout << "[" << a[i] << "] ";
	}
	cout << endl;
	
	cout << "To print the array elements larger than the "
		<< "given number you need to enter a number." << endl;
	cout << "Enter a number: ";
	cin >> num;
	
	printLargerElements(a, size, num);
	system("pause");
	return 0;
}

void printLargerElements(int* a, int size, int num)
{
	cout << "Elements that are larger than the number " << num << " are: " << endl;
	for (int i = 0; i < size; i++)
	{
		if (a[i] > num)
			cout << "[" << a[i] << "] ";
	}
	cout << endl;
}
```

2. **What bug does the original code have?**

  the num is not declared in the code

3. **What misunderstanding of C++ concepts lead you to this incorrect code?**
this bug was there due to lack of concentration only
4. **How to correct the bug?**
add the variables properly
5. **The corresponding bug-free code or code snippet is:**

```
// assignment-4.cpp : This file contains the 'main' function. Program execution begins and ends there.

#include <iostream>
using namespace std;
void printLargerElements(int* a, int size, int num);
//main function
int main()
{
	int a[50];
	int size;
	int num;
	//
	cout << "Enter the size of the array: ";
	cin >> size;
	cout << "Enter the elements into the array: ";
	
	
	cout << "Enter the elements into the array: " << endl;
	for (int i = 0; i < size; i++)
	{
		cout << "a[" << (i + 1) << "]: ";
		cin >> a[i];
		cout << endl;
	}
	
	cout << "The elements entered are: " << endl;
	for (int i = 0; i < size; i++)
	{
		cout << "[" << a[i] << "] ";
	}
	cout << endl;
	
	cout << "To print the array elements larger than the "
		<< "given number you need to enter a number." << endl;
	cout << "Enter a number: ";
	cin >> num;
	
	printLargerElements(a, size, num);
	system("pause");
	return 0;
}

void printLargerElements(int* a, int size, int num)
{
	cout << "Elements that are larger than the number " << num << " are: " << endl;
	for (int i = 0; i < size; i++)
	{
		if (a[i] > num)
			cout << "[" << a[i] << "] ";
	}
	cout << endl;
}

```

6. **What is the take-away message from this bug?**
be carefull all the time you do the assignment
---

# Bug 3

1. **The incorrect original code or code snippit that you wrote:**

```
// assignment-4.cpp : This file contains the 'main' function. Program execution begins and ends there.

#include <iostream>
using namespace std;
void printLargerElements(int* a, int size, int num);
//main function
int main()
{
	int a[50];
	int size;
	int num;
	//
	cout << "Enter the size of the array: ";
	cin >> size;
	cout << "Enter the elements into the array: ";
	
	
	cout << "Enter the elements into the array: " << endl;
	for (int i = 0; i < size; i++)
	{
		cout << "a[" << (i + 1) << "]: ";
		cin >> a[i];
		cout << endl;
	}
	
	cout << "The elements entered are: " << endl;
	for (int i = 0; i < size; i++)
	{
		cout << "[" << a[i] << "] ";
	}
	cout << endl;
	
	cout << "To print the array elements larger than the "
		<< "given number you need to enter a number." << endl;
	cout << "Enter a number: ";
	cin >> num;
	
	printLargerElements(a, size, num);
	system("pause);
	return 0;
}

void printLargerElements(int* a, int size, int num)
{
	cout << "Elements that are larger than the number " << num << " are: " << endl;
	for (int i = 0; i < size; i++)
	{
		if (a[i] > num)
			cout << "[" << a[i] << "] ";
	}
	cout << endl;
}

```

2. **What bug does the original code have?**
the syntax of " is missing at the end 

3. **What misunderstanding of C++ concepts lead you to this incorrect code?**
lack of concentration only.
4. **How to correct the bug?**
be carefull while you perform the code 
5. **The corresponding bug-free code or code snippet is:**

```
#include <iostream>
using namespace std;


int main()
{
	int CAD;
	int USD;
	int A;
	int B;
	int currency{};

	cout << "press 1 to convert USD to CAD" << endl;
	cout << "press 2 to convert CAD to USD" << endl;
	cin >> currency;

	switch (currency) {
	case 1:
		cout << " Enter the amount you want to enter ";
		cin >> currency;
		CAD = currency / 1.32;
		cout << " Your USD equals " << endl;
		cout << CAD << endl;
		break;
	case 2:
		cout << " Enter the amount you want to enter ";
		USD = currency * 0.75;
		cin >> currency;
		cout << " Your CAD equals " << endl;
		cout << USD << endl;
		break;
	default:
		cout << " The currency exchange is... ";
	}

	return 0;


}


```

6. **What is the take-away message from this bug?**
be carefull while u do the assignment
