# Atividade-While-Tabuada
Solicite ao usuário um número inteiro e exiba sua tabuada do 1 ao 10 usando while.

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Ativ.WhileTabuada
{
    public class Program
    {
        static void Main(string[] args)
        {
           
  Console.Write("Digite o Número para Obter a Taboada : ");
            int numero = Int32.Parse(Console.ReadLine());
            int multiplicador = 1;

  while (multiplicador <=10)
            {
                int resultado = numero * multiplicador;
                Console.WriteLine($"{numero}*{multiplicador}={resultado}");
                multiplicador++;
            }

  Console.ReadKey();

  }

        
  }
}
