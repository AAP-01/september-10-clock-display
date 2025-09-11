Project: clock-display
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class ClockDisplay. Then inspect this 
instance and leave the object inspector window open. With the inspector window open, 
call the object's methods, such as timeTick and setTime. Watch the 
"displayString" in the inspector.

The displayString field simulates the actual clock display device. Were this 
program running in a real clock, it would change the real, physical display 
hardware instead of this string. The timeTick method would be triggered once 
every minute by some timer hardware.

Everything else could be pretty much the same.


Note: This project does not implement adequate handling of errors.

Lab 3

21. calling getTime on a ClockDisplay constructor shows "00;00". this is because time hasn't 
started today
22. displayString on the inspector window changes the time to the one i input in the setTime 
method
23. i would have to call timeTick 60 times to reach 01:00 since each call corresponds to a 
minute
24. NumberDisplay digit
    digit = new NumberDisplay(10);
25. Rectanle window;
    window = new Rectangle(int length,int width)
26. public ClockDisplay(int hour, int minute). this constructor generates a time of the day based 
on what the user inputs in the parameters
27. public ClockDisplay() and public ClockDisplay(int hour, int minute) are constructors in the way 
they lack a data type and botth initiate an object, but only the latter has parameters. updateDisplay 
cannot be called because the user isn't meant to update the display ("00:00"), which is instead 
automatically done by the program
28. Printer p1;
    public void print(String filename,boolean doubleSided)
    public int getStatus(int delay)
    
    public  public return getStatus

29. in chapter 1, the constructor Picture creates:
    wall = new Square();
    window = new Square();
    roof = new Triangle();  
    sun = new Circle();
 
30. these are external method calls of the method draw for triangle
    roof.changeSize(60, 180);
    roof.moveHorizontal(20);
    roof.moveVertical(-60);
    roof.makeVisible();
    
31. the Picture class has internal calls:
    wall = new Square();
    window = new Square();
    roof = new Triangle();  
    sun = new Circle();
    drawn = false;

32. (8%3) returns 2 since 2 is the remainder if you divide 8 with 3 and not include decimals
33. (3%1) returns 0
    (3%8) returns 3
    (5%9) returns 5
    (5%-9) returns 5
    (-8%3) returns -2
    (-3%8) returns -3

34. (n%5) can lead to results like 