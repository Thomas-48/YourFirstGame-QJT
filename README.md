# YourFirstGame-QJT
using System;
class Program
{
    static void Main()
    {
        int[] starsPerLine = { 1, 3, 5, 9 }; // Nombre d'étoiles par ligne, à ajuster selon l'image
        for (int i = 0; i < starsPerLine.Length; i++)
        {
            DisplayStars(starsPerLine[i]); // Affiche les étoiles pour chaque ligne
            Console.WriteLine(); // Passer à la ligne suivante
        }
    }
    static void DisplayStars(int count)
    {
        for (int i = 0; i < count; i++)
        {
            Console.Write("*"); // Affiche une étoile suivie d'un espace
        }
    }
}
