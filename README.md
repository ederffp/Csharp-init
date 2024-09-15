<h1> Github exemplos codigos C# </h1>

<p><b> Exemplo: </b></P>

```csharp
using System;

namespace HelloWorld
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello, World!");  
        }
    }
}
```

<p> Nesse exmeplo acima vemos um fragmento de codigo C#, embora simples ele esta recheado de informações importantes que é interessante entender o que cada serve </p>

<h2><b><i> using System; </i></b></h2>

<p> Using System funciona como os imports codigo java, ou seja, ele contém as clases mais fundamentais que todo o codigo C# precisa para ser executado corretamente, como por exemplo mandar uma mensagem de saida(output) para o usuário, precisariamos então da classe Console, portanto seu funcioanmento somente sera possivel se antes tiversmos invocado essa diretiva System.</p>

<h2><b><i> class Program </i></b></h2>

<p> É uma classe que usamos para criar os objetos, é o ponto de partida do nosso programa em C# </p>

<h2><b><i> static void Main(string[] args) </i></b></h2>

<p> Define o nosso metodo Main. Static indica a nos que o metodo - Main - pertence a classe e não a uma instancia da classe. void indica que não há retorno de valor algum. string[] args é um array de strings, que pode ser utlizado para passa argumentos.

