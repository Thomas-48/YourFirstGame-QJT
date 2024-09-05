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
