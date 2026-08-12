using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
        Console.WriteLine ("Enter your name: ");
        string name =Console.ReadLine();
        
        Console.Write("Enter your age:");
        int age =Convert.ToInt32(Console.ReadLine());
        
        Console.Write("Enter your favorite color:");
        string color =Console.ReadLine();
        
        //Comcatination "+ +""
        Console.WriteLine("HELLO " +name+ ", you are " +age+ " years old. your favorite color is " +color+". " );
    }
}
