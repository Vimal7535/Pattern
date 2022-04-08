# Pattern
12


using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp43
{
    class Program
    {
        static void Main(string[] args)
        {
            for (int i = 0; i <=5; i++)
            {
                for (int j = 5-1; j>=i; j--)
                {
                    Console.Write(" ");
                }
                for (int k = 1; k<=i; k++)
                {
                    Console.Write(k);
                }
                Console.WriteLine();
            }
            Console.ReadLine();
        }
    }
}
