string opcao ="";

while (opcao !="s")

{
    Console.Clear();
    Console.Write("deseja cacular qual numero da tabuada ?");
    int n = Convert.ToInt32(Console.ReadLine());

int contador = 1;
while (contador <= 150)
{
int produto = n * contador;

    Console.WriteLine($"{n} x {contador} = {produto}");
    contador++;
}


Console.WriteLine("deseja sair ?");
opcao = Console.ReadLine()!;



}
