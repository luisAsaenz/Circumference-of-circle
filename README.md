# Circumference-of-circle
Creating a Circumference for a Circle using C#
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
