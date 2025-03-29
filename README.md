# 403738308
int d1, m1, y1, d, m, y, a, b, c;
            d = 1;
            m = 1;
            y = 1404;
            a = b = c = 0;

            d1 = int.Parse(Console.ReadLine());
            m1 = int.Parse(Console.ReadLine());
            y1 = int.Parse(Console.ReadLine());

            if (m<=6)
            {
                c = y - (y1+1);     b = 12 - (m1 - m);    a = 31 - d1;
            }
            if (a == 0)
            
            {
                d1 = 31;
            }
            else if (m > 7)
            {
                b = 12 - (m1 - 7);       c = 1404 - y1;            a = 30 - d1;  
            }
            if (a == 0)
            {
                d1 = 30;
                if (b == 12)
                {
                    b = 12; a = 30;
                    
                    
                }
                

            
            }
            Console.WriteLine("day is :" + a);
            Console.WriteLine("month is :" + b);
            Console.WriteLine("year is :" + c);
            Console.ReadLine();
