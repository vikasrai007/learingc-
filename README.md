# learingc-
Learing C# as a beginner 

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace first_project
{
    internal class Program
    {
        static void Main(string[] args)
        {

            // int myNum = 9;
            // float myDoubleNum = 8.99f;
            // char myLetter = 'A';
            // bool myBoolean = false;
            // string myText = "Hello World";
            // Console.WriteLine(myNum);
            // Console.ReadLine();

            // this is not for hen
            /* It is up to you which you want to use */

            // Implicit casting 
            /*float name1 = 4;
            double num = name1;
            Console.WriteLine(num);
            Console.ReadLine();*/

            // Explicit Casting
            /*  double power = 55.5;
              long num = (long) power;
              Console.WriteLine(power);
              Console.WriteLine(num);
              Console.ReadLine();  */

            /*  Type Conversion Methods
             It is also possible to convert data types 
            explicitly by using built-in methods, such as 
            Convert.ToBoolean, Convert.ToDouble, Convert.ToString,
            Convert.ToInt32(int) and Convert.ToInt64(long):  */

            /* double myInt = 10.55;
              int myDouble = 50;
              bool myBool = false;
 
            Console.WriteLine(Convert.ToString(myInt));    // convert int to string
            Console.WriteLine(Convert.ToDouble(myInt));    // convert int to double
            Console.WriteLine(Convert.ToInt32(myDouble));  // convert double to int
            Console.WriteLine(Convert.ToString(myBool));   // convert bool to string  */

            /*  Console.WriteLine("Enter username");
            Console.ReadLine();  */

            Console.WriteLine("Enter your age");
           int Age = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Your Age is: " + Age);
            Console.ReadLine();
        }
    }
}
