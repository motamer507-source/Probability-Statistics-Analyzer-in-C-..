using System;
using System.Collections.Generic;

class Program
{
    static void Main()
    {
        List<double> data = new List<double> { 10, 12, 14, 15, 18, 19, 100 };

        double Q1 = 12;
        double Q3 = 18;
        double IQR = Q3 - Q1;

        Console.WriteLine("\nOutliers:");

        double lowerBound = Q1 - 1.5 * IQR;
        double upperBound = Q3 + 1.5 * IQR;

        foreach (var x in data)
        {
            if (x < lowerBound || x > upperBound)
            {
                Console.WriteLine(x + " is Outlier");
            }
