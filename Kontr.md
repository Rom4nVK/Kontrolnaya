string[] massive;
Console.WriteLine("Ввод массива строк через пробел");
string[] massive;
Console.WriteLine("Ввод массива строк через пробел");
string line = Console.ReadLine();
massive = line.Split(' ');
var result = new string[massive .Length];
int realSize = 0;
foreach (var init in massive )
if (init.Length <= 3)
{
{
result[realSize] = init;
realSize++;
}
}
            
Console.WriteLine("Массивы, содержащие меньше 3 символов -->" + string.Join(Environment.NewLine, result, 0, realSize));