# csharp-console-bootstrapping
Quick drop in to bootstrap the console using reflection.

Just add 

`using Bootstrapping;` 

To the top of your Program.cs, and add the following line to your Main() method.

        static void Main(string[] args)
        {
            typeof(Program).Bootstrap();
        }

