using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace deneme22
{
    internal class Program
    {
        static void Main(string[] args)
        {
            /*I used C# for this bank application code. 
             You can learn account balance with first option or withdraw and deposit money with other options.
            */
            int balance = 3000;

            Console.WriteLine("Welcome to the bank app, please choose a option: ");
            Console.WriteLine("1- Account balance");
            Console.WriteLine("2- Withdraw money");
            Console.WriteLine("3- Deposit money");
            
            string option = Console.ReadLine();

            switch (option)
            {
                case "1":
                    Console.WriteLine("Account balance: "+ balance);
                    Console.ReadLine();
                    break;
                
                case "2":
                    Console.WriteLine("How much money do you want to withdraw?");
                    int withdraw = Convert.ToInt32(Console.ReadLine());

                    if (withdraw > balance)
                    {
                        Console.WriteLine("You can't withdraw money because you don't have enough money!");
                        Console.ReadLine();
                    }

                    else 
                    {
                        Console.WriteLine("Your currently balance: " + (balance - withdraw));
                        Console.ReadLine();
                    }
                    break;

                case "3":
                    Console.WriteLine("How much money do you want to deposit?");
                    int deposit = Convert.ToInt32(Console.ReadLine());
                    Console.WriteLine("Your currently balance: " + (balance + deposit));
                    Console.ReadLine();
                    break;

                default:
                    Console.WriteLine("Error...");
                    Console.ReadLine();
                    break;
            }
        }
    }
}
