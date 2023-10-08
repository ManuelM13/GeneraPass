# GeneraPass
GeneraPass es un proyecto muy básico, genera contraseñas en base a dígitos que introducimos a través de una consola de comandos.
-----------------------------------------------------------------------------------------------------------------------------------------

El código fuente está creado en C# y es el siguiente:

namespace generapass
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int a = 0;
            int b = 0;
            

            Console.Write("ESCRIBE NUMERO FAVORITO  ");
            a = Int32.Parse(Console.ReadLine());

            Console.Write("ESCRIBE EL SEGUNDO NUMERO FAVORITO  ");
            b = Int32.Parse(Console.ReadLine());

            Console.Write("ESCRIBE LA SEGUNDA LETRA DE TU NOMBRE   ");
            char c1 = Console.ReadKey().KeyChar;

            Console.ReadLine();

            Console.Write("ESCRIBE LA TERCERA LETRA DE TU APELLIDO EN MAYUSCULAS   ");
            char c2 = Console.ReadKey().KeyChar;

            Console.ReadLine();

            Console.Write("PRIMERA LETRA DE TU SEGUNDO APELLIDO  ");
            char c3 = Console.ReadKey().KeyChar;

            Console.ReadLine();


            Console.Write("PASS:    ");
             
            Console.Write(a + b);

            Console.Write(a * b);

            Console.Write(c1);

            Console.Write(a + a + b * 2);

            Console.Write(c2);

            Console.Write(a * b * 5);

            Console.Write(c3);

            Console.Write(a * 3 + b);

            Console.ReadLine();

            Console.WriteLine("GURADA TU CONTRASEÑA EN UN LUGAR SEGURO, SALUDOS .");


            Console.ReadLine();
        }
    }
}
