C notes here:

Before Coding:
-C does not have built-in functions so ---> must provide toolkits first
-Use #include <> ---> inside <>, stdio.h (gives printf() and scanf()), stdint.h (gives fixed-width integers), stdbool.h (gives booleans)), <inttypes.h> (for stdint.h and string macros)
-Optional but Standard: #define to define the global settings or configuration numbers
-begin code with int main(){: defines program starting point
-if using fixed-width types, declare them inside main and replace the type with fixed-width (uint8_t, uint16_t, int8_t, int16_t etc.)

-complete code with return 0;}
Blocks:
-Blocks are group with {} instead of indentations
-Variables inside blocks/loops are always local

Types and Variables:
-Print statements (printf()) are similar to python except a new print statement does not create a new line unless the \n is utilized in the previous print statement
-begin code with int main(): defines program starting point
-complete code with return 0;
-When writing variables include: type of information variable will store (eg. numbers, text, decimals, characters)
-Format for variables is: (type (eg. char, int, double, float), name of variable (anything), [] (if storing multiple of type), = , value;)
-To call a variable in a print function: (%s (string), %d (number/integer) ( in printf string (placeholder), ,variable name (outside of print string))

**IMPORTANT: Fixed width types are data types that have an exact size of bits such as 8 or 16. They guarantee a specific number of bits for memory, regardless of the hardware. They are used to help no avoid sizing differences and are utilized in hardware since hardware typically has an exact size.
By utilizing a fixed width type, we can make sure that the software that is created will align perfectly with the hardware's footprint. 

