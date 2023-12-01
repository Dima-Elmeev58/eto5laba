# eto5laba
Console.WriteLine("Введите N");
int N = Convert.ToInt32(Console.ReadLine());
int[] A = new int[N];
foreach (int i in A)
{
    int x = Convert.ToInt32(Console.ReadLine());
}
int min = A[0];
for (int i = 1; i < N; i++)
{
    if (A[i] < min)
    {
        min = A[i];
    }
}
int max = A[0];
for (int i = 1;i < N; i++)
{
    if ((A[i] > max))
    {
        max = A[i];
    }
}
int temp = min;
min = max;
max = temp;
