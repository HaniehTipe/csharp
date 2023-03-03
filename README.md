برنامه ای بنویسید که دو عدد جست وجو شده در آرایه 10*10را بصورت ستونی پیمایش کند(c#)
using System;
namespace project { 
class Test
    {
public static void Main()
        {
            int[10, 10] a;
            int i = Convert.ToInt32(Console.ReadLine());
            int j = Convert.ToInt32(Console.ReadLine());
            for (i = 0; i < 10; i++)
            {
                for (j = 0; j < 10; j++)
                {
                    [10,10]a= Convert.ToInt32(Console.ReadLine());
                }
            }
            int number= Convert.ToInt32(Console.ReadLine());
            int temp = 0;
            int i = Convert.ToInt32(Console.ReadLine());
            int j = Convert.ToInt32(Console.ReadLine());
            for (i = 0; i < 10; i++)
            {
                for (j = 0; j < 10; j++)
                {
                    if (number ==[j, i]a){
                temp++;
           
            }
                }
            }
        }
        برنامه ای بنویسد که یک آرایه دو بعدی3*3را از ورودی بخواندودترمینان آن رادر خروجی نمایش دهد(c#)
       using System;
namespace project
{
    class Test
    {
        public static void Main()
        {
            int[3, 3] a;
            int det = 0;
            int i = Convert.ToInt32(Console.ReadLine());
            int j = Convert.ToInt32(Console.ReadLine());
            for (i = 0; i < 3; i++)
            {
                for (j = 0; j < 3; j++)
                {
                    [3,3]a = Convert.ToInt32(Console.ReadLine());
                }
            }
            det =[0, 0]a * ([1, 1]a *[2, 2]a * -[2, 1]a *[1, 2]a)-[1, 0]a * ([0, 1]a *[[2, 2]a]-[2, 1]a *[0, 2]a)+[2, 0]a * ([0, 1]a*[1,2]a-
                [1, 1]a*[0,2]a);
            Console.WriteLine(det);
        }
    }
} 
