# first

using System;


namespace ConsoleApp3
{
    class Program
    {
        
        static void Main(string[] args)
        {
            int[,] mass = new int[7, 7];
            

            Random r = new Random();

            for (int i = 0; i < 7; i++)
            {
                for (int j = 0; j < 7; j++)
                {
                    mass[i, j] = r.Next(2);
                    Console.Write(mass[i, j]);
                }
                Console.WriteLine();

                void fill(int x, int y, int c, int d, int[][] m)
                {
                    if (i>=0 && y>=0 )
                }
            }

            
            
            



        }


    }
}
