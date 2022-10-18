# вар 2.24
using System;
 
class Program
{
    static void Main()
    {
        for (int i = 100; i < 999; i++)
        {
            if ((i % 10).ToString() + ((i - i % 10) / 10).ToString() == "237")
            {
                Console.WriteLine(i);
                break;
            }
        }
        Console.ReadKey();
    }
}
