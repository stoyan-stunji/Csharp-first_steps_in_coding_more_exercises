using System;

namespace _05_Training_Lab
{
    internal class Program
    {
        static void Main(string[] args)
        {
            double w = double.Parse(Console.ReadLine());
            double h = double.Parse(Console.ReadLine());

            double hCM = h * 100;
            double wCM = w * 100;

            double hCMCorridor = hCM - 100;
            double buroPerRow = Math.Floor(hCMCorridor / 70);

            double rows = Math.Floor(wCM / 120);

            double places = (rows * buroPerRow) - 3;

            Console.WriteLine(places);

        }
    }
}
