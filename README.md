# Ijunior-Ex2
using System;

class Program
{
    static void Main(string[] args)
    {
        string nameCharacter = "Kuro";
        int skillPoints = 0;
        double healthValue = 100.0;
        char startPosition = 'N';
        float height = 190f;
        bool isRide = false;
        ushort speed = 10;
        byte levelCharacter = 1;
        short manaPoints = 50;
        uint levelPoints = 0;

        Console.WriteLine($"Name-{nameCharacter}\t \n Health: Level: {levelCharacter} \t \n Height: {height} \t \n HP:{healthValue} \t \n SP:{skillPoints} \t \n MP:             {manaPoints} \t \n Level: {levelPoints}/1000 \t \n Speed: {speed} \t \n Position: {startPosition} \t \n Ride - {isRide} ");
    } 

}
