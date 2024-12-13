using System.Buffers;
using System.ComponentModel.Design;
using System.Runtime.CompilerServices;

namespace MATUTINA
{
    internal class Program
    {

        static void Main(string[] args)
        {
            Console.Write("react or skip");

            string[] groups = { "angelo", "mark", "trixie", "philip", "llyod", "jazz", "chris", "chean", "gab", "dess" };
            
            for (int i = 0; i < groups.Length; i++)
            {
                int all_skips = 0;
                int all_like = 0;
                int all_disliike = 0;


                Console.Write(groups[i]);
                Console.WriteLine("react");
                Console.WriteLine("skip");
                string pick = Convert.ToString(groups[i]);

                if (pick == "react")
                {

                    Console.Write(groups[i]);
                    Console.WriteLine("like");
                    Console.WriteLine("dislike");
                    string react = Convert.ToString(groups[i] + " " + groups[i]);

                }

                else (pick == " skip ") 
                {
                    Console.Write(groups[i]);
                    Console.WriteLine("like");
                    Console.WriteLine("dislike");
                    string react = Convert.ToString(groups[i] + " " + groups[i]);
                }
                
                






            }
        }
