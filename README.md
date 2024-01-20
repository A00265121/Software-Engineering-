Console.WriteLine("Hello, Dears!");

        //bicycle 1 Details//
        var bicycle1name = "Harly";
        int bicycle1wheelsize = 20;
        var bicycle1color = "Blue";
        int bicycle1price = 1000;

        //bicycle 2 Details//
        var bicycle2name = "Hero";
        int bicycle2wheelsize = 22;
        var bicycle2color = "Black";
        int bicycle2price = 900;

        //Conversion factor//

        Double conversionUSD= 1.2;

        Console.WriteLine("\n\n Canadian Products");
        Console.WriteLine("\n\nBicycle Name:" + bicycle1name + "\n\nBicycle Color:" + bicycle1color  + "\n\nBicycle Wheel Size (INCH):" +
            +bicycle1wheelsize + "n\nBicycle Price:" + bicycle1price);

        Console.WriteLine("\n\n United States Products");
        Console.WriteLine("\n\nBicycle Name:" + bicycle2name + "Bicycle Color:" + bicycle2color + "\n\nBicycle Wheel Size (INCH):" +
            +bicycle2wheelsize + "\n\nBicycle Price:" + bicycle2price/conversionUSD);

        Console.ReadLine();
