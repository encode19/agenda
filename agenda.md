# agenda

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp4
{

    class aliens
    {
        public int edad = 10;
        public string nombre;
        string planeta;
        string raza;
    }

class Program // hacer array de objetos y darles nombres.
    {
        static void Main(string[] args)
        {
            aliens[] a = new aliens[5];
            for (int i = 0; i < 5; i++)
            {
                a[i] = new aliens();
            }
            a[2].nombre = "eric";
            Console.WriteLine(a[2].nombre);

            Console.ReadKey();
        }
    }
}
