# Taller-1-scripting
## 20 firmas diferentes de funciones
```c# 
using System;
using System.Collections.Generic;

class Program
{
    static void Saludar() {}
    static void Despedir(string nombre) {}
    static int ObtenerNumeroAleatorio() { return 0; }
    static int Sumar(int a, int b) { return 0; }
    class Persona { public string Nombre { get; set; } public int Edad { get; set; } }
    static void MostrarPersona(Persona persona) {}
    static void MostrarArray(int[] numeros) {}
    static string ObtenerSaludo(string nombre) { return ""; }
    static void MostrarLista(List<string> nombres) {}
    static void MostrarMatriz(int[,] matriz) {}
    static int Factorial(int n) { return 0; }
    static bool EsPar(int numero) { return false; }
    static double CalcularAreaCirculo(double radio) { return 0.0; }
    static void ImprimirMensaje(string mensaje, int veces) {}
    static DateTime ObtenerFechaActual() { return DateTime.Now; }
    static char ObtenerPrimeraLetra(string texto) { return ' '; }
    static void MezclarListas(List<int> lista1, List<int> lista2) {}
    static string ConcatenarCadenas(string str1, string str2) { return ""; }
    static float CalcularPromedio(float[] valores) { return 0.0f; }
    static void ProcesarDatos(Dictionary<string, int> datos) {}
    static long CalcularFactorialIterativo(int n) { return 0; }
    static void Main() {}
}
```


## Retos de manejo de terminal

![Captura de pantalla 2025-01-30 182305](https://github.com/user-attachments/assets/70c4ef69-fa4b-44e3-9fd6-b2a80b6892e0)

![Captura de pantalla 2025-01-30 182403](https://github.com/user-attachments/assets/58282006-b06a-4673-bbe3-4db13164e979)

![Captura de pantalla 2025-01-30 185548](https://github.com/user-attachments/assets/4659803c-b4be-4fc1-b5bc-c239f1900550)


## RESPUESTA PREGUNTAS DE TEORIA

### 1. ¿Qué es un ciclo infinito?

Un ciclo infinito es un bucle que nunca termina porque su condición de salida nunca se cumple. Esto puede hacer que el programa se bloquee o consuma muchos recursos hasta que sea detenido manualmente.
```c#
using System;

class Program
{
    static void Main()
    {
        while (true) // La condición siempre es verdadera, el bucle nunca se detiene
        {
            Console.WriteLine("Esto es un ciclo infinito...");
        }
    }
}
```
### 2. ¿Qué es un error en tiempo de ejecución?

Un error en tiempo de ejecución ocurre cuando un programa se ejecuta y encuentra una situación inesperada, como división por cero, acceso a índices fuera de rango o referencias nulas. Esto provoca que el programa se detenga abruptamente a menos que se maneje correctamente.
```c#
using System;

class Program
{
    static void Main()
    {
        int divisor = 0;
        int resultado = 10 / divisor; // Error en tiempo de ejecución: división por cero
        Console.WriteLine($"El resultado es: {resultado}");
    }
}
```


