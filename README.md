# Circumference-of-circle
// Creating a Circumference for a Circle using C#. I applied user interface so that the user can input their own radius

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
