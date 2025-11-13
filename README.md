# clase-dise-o-de-aplicaciones-de-ultima-generacion
--codigo1
using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
        Console.Write("Ingrese su nombre completo: ");
        string nombre = Console.ReadLine();
        Console.WriteLine("su nombre es: "+nombre);
    }
}
--codigo2
using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
        Console.Write("Ingrese su nombre completo: ");
        string nombre = Console.ReadLine();
        Console.WriteLine("su nombre es: "+nombre);
    }
}
--codigo3
using System;

public class programa1
{
    public static void Main(string[] args)
    {
        string nombre = "Juan Camilo Ibarra Sanchez";
        int edad = 18;
        Console.WriteLine("Nombre: " + nombre + ", Edad: " + edad);
    }
    }
  --codigo4
  using System;

public class programa1
{
public static void Main(string[] args)
{
string nombre = "Juan Camilo Ibarra Sanchez";
int edad = 18;
Console.WriteLine(String.Format("Nombre: {0}, Edad: {1}", nombre, edad));
}
}
