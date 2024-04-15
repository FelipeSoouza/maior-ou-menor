using System;

namespace MaiorOrMenor
{
    class Program
    {
        static void Main(string[] args)
        {
            Int64 Number1;
            Int64 Number2;

            Console.Write("Digite um número: ");
            Number1 = Convert.ToInt64(Console.ReadLine());

            Console.Write("Digite outro número: ");
            Number2 = Convert.ToInt64(Console.ReadLine());


            if (Number1 > Number2)
            {
                Console.WriteLine("O " + Number1 + " É maior que " + Number2);
            }

            else
            {
                Console.WriteLine("O " + Number1 + " É menor que " + Number2);
            }
        }
    }
}
