# StringLib

This is a simple library for learning string functions.

## Features
- Get string length  
- Convert to upper / lower case  
- Reverse string  
- Join (concat) two strings   
- Replace part of a string   
- Trim spaces  

## Example
```c++
#include <iostream>
#include "String.h"
int main()
{
	clsString::clsStr_Change_Letter_UpperLower_Fun Str_1;

	Str_1.SetString("Hello");
	Str_1.SetChar('H');

	Str_1.ChangeStringToUpper();
	cout << "After update: " << Str_1.GetString();

	return 0;
}
```
## Note
- this project lib, it is educational  lib
- I created it to learn
- In this code , I know I have problems,
- but i don’t have time to solve everything, that why I will to go to next project
- If you have any ideas please comment
- thanks for your time


