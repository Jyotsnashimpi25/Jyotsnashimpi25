### Hi there š

<!--
**Jyotsnashimpi25/Jyotsnashimpi25** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
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
