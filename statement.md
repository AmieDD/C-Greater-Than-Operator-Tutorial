# C# > Operator Tutorial
This C# > Operator Tutorial www.amiedd.com AmieDD - code, cosplay and games


```C# runnable
using System;

using System;

class GreaterThan
{
 static void Main()
    {
Console.WriteLine(9.0 > 2.1);   //True
Console.WriteLine(1.3 > 1.3);   //False
Console.WriteLine(0.0 > 2.1);   //False

Console.WriteLine(double.NaN > 2.1);   //False
Console.WriteLine(double.NaN <= 2.1);  //False
    }
}


```

# C# > Operator

> "Greater Than" relationship operator will return true if the first operator is greater than the second, if not it returns false. This applies to numeric and enumerations types

In Game Hint: Relational operators like greater than and less than >, <, . If the operator IS NOT a number, example Double.NaN or Single.NaN the operation result will be FALSE. If the NaN value isn't greater than, less tha, equal to any DOUBLE or FLOAT value. 

## Example: This will return false

Double zero = 0;

if ((0 / zero) == Double.NaN) 
   Console.WriteLine("0 / 0 can be tested with Double.NaN.");
