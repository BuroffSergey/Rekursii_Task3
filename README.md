# Rekursii_Task3



Решение задачи.


using System;

class Program
{
    static void PrintArrayReverse(int[] arr, int index)
    {
        if (index >= 0)
        {
            Console.Write(arr[index] + " "); 
            PrintArrayReverse(arr, index - 1); 
        }
    }

    static void Main()
    {
        // Произвольный массив (замените значения на свои)
        int[] myArray = { 1, 2, 10, 4, 83 };

        PrintArrayReverse(myArray, myArray.Length - 1);
    }
}
