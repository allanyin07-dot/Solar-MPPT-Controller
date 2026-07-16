C notes here:

Before Coding:
-C does not have built-in functions so ---> must provide toolkits first\
-Use #include <> ---> inside <>, stdio.h (gives printf() and scanf()), stdint.h (gives fixed-width integers), stdbool.h (gives booleans)), <inttypes.h> (for stdint.h and string macros)\
-Optional but Standard: #define to define the global settings or configuration numbers\
-Begin code with int main(){: defines program starting point\
-if using fixed-width types, declare them inside main and replace the type with fixed-width (uint8_t, uint16_t, int8_t, int16_t etc.)\
-complete code with return 0;}

Blocks:\
-Blocks are group with {} instead of indentations\
-Variables inside blocks/loops are always local

Types and Variables:\
-Print statements (printf()) are similar to python except a new print statement does not create a new line unless the \n is utilized in the previous print statement\
-begin code with int main(): defines program starting point\
-complete code with return 0;\
-When writing variables include: type of information variable will store (eg. numbers, text, decimals, characters)\
-Format for variables is: (type (eg. char, int, double, float), name of variable (anything), [] (if storing multiple of type), = , value;)\
-To call a variable in a print function: (%s (string), %d (number/integer) ( in printf string (placeholder), ,variable name (outside of print string))

Arrays:\
-Used to store pieces of info\
-A type of data structure that can store multiple different data values without needing to create a separate variable for each individual piece of data\
-Can only hold one type of data (char, int, double, etc.)\
-Fixed data set, cannot change number of elements once created\
-To change element in array, like in python, name of array [index #] = new element;\
-If you want to create an array but do not want to store the data in it because of different reasons, you can create an empty array like such:\
type of array, name of array [specifiy # of elements that can be stored in array];\
-Since an array is fixed, you have to state the amount of information an array can hold\
-If an empty index from an array is called, -2 will be displayed\
-To create an array: classify type of data being stored (int, char, double), name of array, [] (tells it is an array), = , {data separated by commas}, ;\
-To access an element in print function: printf ("%(type of array)", name of array[index #]);

For loops:\
-Structure: for (initial condition (an initial variable), condition (what to be evaluated before each repetition), update (runs at end of iteration, modifies loop variable)

**IMPORTANT: Fixed width types are data types that have an exact size of bits such as 8 or 16. They guarantee a specific number of bits for memory, regardless of the hardware. They are used to help no avoid sizing differences and are utilized in hardware since hardware typically has an exact size.\
By utilizing a fixed width type, we can make sure that the software that is created will align perfectly with the hardware's footprint.

**IMPORTANT: A STRING IS AN ARRAY OF CHARACTERS

