### Hi there 👋

<!--
**Jyotsnashimpi25/Jyotsnashimpi25** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace ConsoleApplication1
{
    
    class Program
    {
        static void Main(string[] args)
        {
            int i     = 0;

            Console.WriteLine("Even Numbers :");
            for (i = 1; i <=10; i++)
            {   
                if( i%2 == 0 )
                {
                    Console.Write( i +" " );
                }
            }
        }
        
    }
}
