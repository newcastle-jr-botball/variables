# VARIABLES
This is a small basic script helping to explain variables to elementary students. 

Variables are a means to store data in our scripts. Let's say we want to store how many apples we have. We may need to access this information from many places within our script. If we have a lot of apples, we don't want to have to count them every time we need to know how many we have. This is an example of where a *variable* would come in. 

Let's say we have 148 apples.

You can think of a variable as a labeled box. We can take a box and put the number 148 inside of it. Then, on the outside of the box, we can put a label on it. Let's call it "number_of_apples". So, every time that we need to know how many apples we have, we just need to access that box and see what the number is inside the box: 148.

In code, we do just about the same thing. We "name" our variable (number_of_apples), and set a "value" to it (148). This is what it looks like:

    int number_of_apples = 148;

* The __int__ tells us what type of data we want to store (it's called a data type - we'll learn that in a later lesson) -- for now, when we want to store a whole number, we use "int" which is short for integer.
* The next section is the __label__ - what we want to call our variable.
* The next is the __assignment__ which is the equals sign (=) - We are setting the value of number_of_apples "equal to" 148.
* The next part is the __value__: 148.

We can use our variable by name:

     printf("We have %d apples.\n", number_of_apples);

This will print "We have 148 apples." to the console. Or in a conditional:

    if (number_of_apples == 148) {
        // yes, we have 148 apples
    }

And we can __reassign__ a new value at any time within our code. Let's say we've dropped 10 of our apples. We can then do this:

    number_of_apples = 138;
    //Or, we can calculate the number directly:
    number_of_apples = number_of_apples - 10; // this will assign the result to number_of_apples

In this way, the value of the variable __varies__ - it can change at any time. That is where we get the name.


*Note:*

The code used in these tutorials is intended to run on the KIPR Link controller and written in 
the KISS Platform. You can find information about the KIPR Link and KISS Platform at 
http://www.kipr.org/hardware-software. The KISS Platform includes a simulator, so you can run 
the code on your computer without a robot. Our Botball team currently participates in the Junior 
Botball Challenge sponsored by KIPR. You can view more information for the challenge at 
http://www.juniorbotballchallenge.org.
