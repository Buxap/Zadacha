# Zadacha
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApplication31
{
    class Program
    {
        static void Main(string[] args)
        {
            int a = 238;
            int b = 345;
            int min = Math.Min(a, b);
            int max = Math.Max(a, b);
            if (min < max)
            {
                Console.WriteLine(max);
            }

        }
    }
}
