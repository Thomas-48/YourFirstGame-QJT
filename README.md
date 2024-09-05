# YourFirstGame-QJT
// Online C# Editor for free
// Write, Edit and Run your C# code using C# Online Compiler
using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
        int c; 
        func_1();
    }
    public static void func_1(){
         int x=1;
         Console.WriteLine ("test");
         for (int i=0;i<5;i++){
            for (int y=0;y<x;y++){
                if (x==7) {
                    continue;
                }
                Console.Write ("*");
            }
        if (x==7) {
            x=x+2;
            continue;
                }
        Console.WriteLine ();
        x=x+2;
         }
    }
   
}
#deuxème solution
// Online C# Editor for free
// Write, Edit and Run your C# code using C# Online Compiler

using System;
class Program
{
    static void Main()
    {
        int[] starsPerLine = { 1, 3, 5, 9 };
        for (int i = 0; i < starsPerLine.Length; i++)
        {
            DisplayStars(starsPerLine[i]); 
            Console.WriteLine(); 
        }
    }
    static void DisplayStars(int count)
    {
        for (int i = 0; i < count; i++)
        {
            Console.Write("*"); 
        }
    }
}
