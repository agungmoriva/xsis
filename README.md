# Logic01Soal01
            int n = 9;
            int nT = (n - 1) / 2;
            Console.WriteLine("1. ");
            Console.WriteLine();
            for (int i = 0; i < n; i++)
            {
                for (int j = 0; j < n; j++)
                {
                    if (i==j)
                    {
                        Console.Write("* ");
                    }else
                    {
                        Console.Write("  ");
                    }
                }
                Console.WriteLine();
            }
