using System;

namespace Trane
{
    class Program
    {
        static void Main(string[] args)
        {
            int des;
            Console.Write("Enter first number: ");
            int num1 = Convert.ToInt32(Console.ReadLine());
            Console.Write("Enter second number: ");
            int num2 = Convert.ToInt32(Console.ReadLine());
            Console.Write("Enter a number of operation: ");
            int operationNum = Convert.ToInt32(Console.ReadLine());
            switch (operationNum)
            {
                case 1:
                    Console.WriteLine("This is addition operation.");
                    des = num1 + num2;
                    Console.WriteLine($"The result of operation is: {des}");
                    break;
                case 2:
                    Console.WriteLine("This is subtraction operation");
                    des = num1 - num2;
                    Console.WriteLine($"The result of operation is: {des}");
                    break;
                case 3:
                    Console.WriteLine("This is multiplication operation");
                    des = num1 * num2;
                    Console.WriteLine($"The result of operation is: {des}");
                    break;
                default:
                    Console.WriteLine("Unexpected operation");
                    break;
            }
        }
    }

}
