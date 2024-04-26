# 19AI308-Object-Oriented-Programming-using-CSharp--Ex6---Recursive-Function
# Aim: 
To write a C# program to reverse a number using recursive function.

# Algorithm:
## Step 1:
 Declare variables for the input number and its reverse, initializing the reverse as 0.
## Step 2:
 Prompt the user to enter a number and read the input.
## Step 3:
 Start a loop that continues until the input number becomes 0.
## Step 4:
 Inside the loop, update the reverse by adding the last digit of the input number.
## Step 5:
 Remove the last digit from the input number.
## Step 6:
 Display the reversed number to the user.
 
# Program:
```
Developed by : G.Jayanth.
Register no  : 212221230030.
```
```c#
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace Program
{
    class Program
    {
        static void Main(string[] args)
        {
            int num, reverse = 0;
            Console.Write("Enter a Number : ");
            num = int.Parse(Console.ReadLine());
            while (num != 0)
            {
                reverse = reverse * 10;
                reverse = reverse + num % 10;
                num = num / 10;
            }
            Console.WriteLine("Reverse of Entered Number is : " + reverse);
            Console.ReadLine();

        }
    }
}
```

# Output:
<img width="960" alt="image" src="https://github.com/JayanthYadav123/19AI308-Object-Oriented-Programming-using-CSharp--Ex6---Recursive-Function/assets/94836154/90c2544c-9df1-4bc8-9ab2-9dde1466a161">

# Result:
The program for reversing a number using a recursive function has been successfully executed.
