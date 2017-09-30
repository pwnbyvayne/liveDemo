# liveDemo
demoSoftUni

namespace tech_module___ex_1
{

    using System;
    class Program
    {
        static void Main(string[] args)
        {

            int numberOne = int.Parse(Console.ReadLine());
            int numberTwo = int.Parse(Console.ReadLine());


            if (numberOne < numberTwo)
            {
                for (int i = numberOne; i <= numberTwo; i++)
                {
                    Console.WriteLine(i);
                }

            }
           else if (numberOne > numberTwo)
            {
                for (int i = numberTwo; i <= numberOne; i++)
                {
                    Console.WriteLine(i);
                }

            }








        }

    }
}
