using System;

class Program
{
    static void Main()
    {
        
        string nombre;
        int edad;
        double peso;
        double estatura;
        bool tieneSeguro;
        double imc;

     {
        Console.Write("Ingrese el nombre del paciente: ");
        nombre = Console.ReadLine();

        Console.Write("Ingrese la edad: ");
        edad = int.Parse(Console.ReadLine());

        Console.Write("Ingrese el peso : ");
        peso = double.Parse(Console.ReadLine());

        Console.Write("Ingrese la estatura : ");
        estatura = double.Parse(Console.ReadLine());

        Console.Write("Tiene seguro? (S/N): ");
        string respuestaSeguro = Console.ReadLine().ToUpper();

        tieneSeguro = respuestaSeguro == "S";

      
        imc = peso / (estatura * estatura);
     }

      {
        Console.WriteLine("\n----- FICHA MEDICA DEL PACIENTE -----");
        Console.WriteLine("Nombre: " + nombre);
        Console.WriteLine("Edad: " + edad + " annos");
        Console.WriteLine("Peso: " + peso + " kg");
        Console.WriteLine("Estatura: " + estatura + " m");
        Console.WriteLine("Tiene seguro: " + (tieneSeguro? "Si" : "No"));
        Console.WriteLine("IMC: " + imc.ToString("F2"));
      }
       

        Console.ReadKey();
    }
}
