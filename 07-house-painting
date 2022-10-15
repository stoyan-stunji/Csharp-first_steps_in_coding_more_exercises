using System;

namespace _07_House_Painting
{
    internal class Program
    {
        static void Main(string[] args)
        {
            double x = double.Parse(Console.ReadLine());
            double y = double.Parse(Console.ReadLine());
            double h = double.Parse(Console.ReadLine());

            //Walls - Green
            double window = 1.5 * 1.5;
            double sideWall = (x * y) - window;
            double bothSideWalls = sideWall * 2;

            double door = 1.2 * 2;
            double backWall = x * x;
            double frontWall = backWall - door;
            double bothMainWalls = backWall + frontWall;

            double wallsArea = bothSideWalls + bothMainWalls;

            double green = wallsArea / 3.4;

            //Roof - Red
            double slant = x * y;
            double bothSlants = 2 * slant;

            double front = x * h / 2;
            double bothFronts = 2 * front;

            double roofArea = bothFronts + bothSlants;

            double red = roofArea / 4.3;

            Console.WriteLine($"{green:f2}");
            Console.WriteLine($"{red:f2}");

        }
    }
}
