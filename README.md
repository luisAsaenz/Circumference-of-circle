Using C# I created a circumference for a circle that requires user input

namespace CircleCumference
{
    class Program
    {
        static void Main(string[] args)
        {

            double pI = Math.PI;

            double r;
            r = Convert.ToDouble(Console.ReadLine());

            if (r > 0)
            {
                double circumference = 2 * r * pI;
                Console.WriteLine("The Circumference is: " + circumference);
            }

        }
    }
}
