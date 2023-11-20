#POO 
Inheritance (ou Herança) é um conceito de POO que permite que classes herdem propriedades e comportamentos de outras classes. Isso permite a criação de hierarquias e promovem a reutilização de código e modularidade. Objetos que herdam de outros também podem ser identificados como tipos daquele objeto base, podendo ter seus dados herdados referenciados como tal.

Normalmente, existe uma classe base como por exemplo, uma classe `Carro` de onde outros modelos derivados vão existir, tais como `Toyota, Camaro, Lamborghini` e irão herdar as propriedades bases de um carro.

### Exemplo:
```cs
using System;

public class Car
{
    public string Make { get; set; }
    public string Model { get; set; }
    public int Year { get; set; }

    public virtual void Drive()
    {
        Console.WriteLine("Carro começou a dirigir");
    }

    public void Stop()
    {
        Console.WriteLine("O carro parou");
    }
}

public class Toyota : Car
{
    public bool Hybrid { get; set; }

    public override void Drive()
    {
        Console.WriteLine("O Toyota ta dirigindo suavemente.");
    }
}

public class Camaro : Car
{
    public int Horsepower { get; set; }

    public override void Drive()
    {
        Console.WriteLine("O Camaro ta dirigindo rapidamente");
    }
}

public class Program
{
    public static void Main(string[] args)
    {
        Toyota toyotaCamry = new Toyota
        {
            Make = "Toyota",
            Model = "Camry",
            Year = 2022,
            Hybrid = true
        };

        Camaro chevroletCamaro = new Camaro
        {
            Make = "Chevrolet",
            Model = "Camaro",
            Year = 2022,
            Horsepower = 455
        };

        Console.WriteLine(toyotaCamry.Make);
        Console.WriteLine(chevroletCamaro.Model);

        toyotaCamry.Drive();
        chevroletCamaro.Stop();
    }
}

```