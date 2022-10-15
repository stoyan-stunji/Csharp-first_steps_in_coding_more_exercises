using System;

namespace _06_Fishland
{
    internal class Program
    {
        static void Main(string[] args)
        {
            double priceMackerel = double.Parse(Console.ReadLine());
            double priceSprinkle = double.Parse(Console.ReadLine());
            double bonitoKG = double.Parse(Console.ReadLine());
            double scadKG = double.Parse(Console.ReadLine());
            int musselsKG = int.Parse(Console.ReadLine());
            double priceMussels = 7.5;

            double priceBonito = priceMackerel + priceMackerel * 0.6;
            double sumBonito = bonitoKG * priceBonito;

            double priceScad = priceSprinkle + priceSprinkle * 0.8;
            double sumScad = scadKG * priceScad;

            double sumMussels = musselsKG * priceMussels;

            double priceFinal = sumBonito + sumScad + sumMussels;

            Console.WriteLine($"{priceFinal:f2}");

        }
    }
}
