# Debit-Card-Number
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Debit_Card_Number
{
    class Program
    {
        static void Main(string[] args)
        {
            int firstNum = int.Parse(Console.ReadLine());
            int secondNum = int.Parse(Console.ReadLine());
            int thirdNum = int.Parse(Console.ReadLine());
            int fourthNum = int.Parse(Console.ReadLine());

            Console.Write($"{firstNum:d4} ");
            Console.Write($"{secondNum:d4} ");
            Console.Write($"{thirdNum:d4} ");
            Console.WriteLine($"{fourthNum:d4}");
        }
    }
}
