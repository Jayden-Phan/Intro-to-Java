Java file = all of our code
.md file = Text, definitions, etc;
## Intro to Java
A Java program can be characterized as an **object**
represented in **class**. Currently our program has a *main* object. Inside the object we have the *Main* class.

## Output
In Java to output and item to the console we use: 'System.out.print()' and 'System.out.println()'
`System.out.println()` prints the statement and moves to the next line, while `System.out.print` just prints the statement.

## Comments
A comment is used as a user annotation with the purpose of being human readable. **Line Comments** follow double backslashes. `//`**Block Comments** are contained within the `/* comments */`

## Indentifiers 

In Java use the term **Indentifiers** to describe a variable,parameter, constant, user-defined, method or user defined class.

- Cannot begin with digit
- Can only contain letters, digits, and underscores
- Case-senitive `/*age!= Age`

*Note: *
- class starts with a capital letter
- reserved words are entirely lowercase and may not be used as Indentifiers (Reserved words will show up in blue)

## Types
**Primitive** or **Built-In** types of in Java are 

- `int` an integer 
- `boolean` true or false.(boolean shirt color = true)
- `double` floating-point number (2.73) (comapared to float in Python)
- `char` single character



*Note: * Integers have a fixed amount of memory, so there is a limit to how many digits you can store(2^31-1)

## Variables 
Varibales are a type of indentifier that stores value of a specific type

we can create variables using **declaration**
- `int age;`
- `double x, y;`
- `boolean found;`
- `char letter; `



We can also initialize a variable in its **declaration**

- `int count = 1;`
- `x = 2.0`
- `double p = 3.14;`
- `char c = '8'; `

## Chars

[ASCI CHART]
https://docs.google.com/document/d/1oubLTqAHmdkadtjbR8xxREG7auvuUqiQ/edit

Each character is associated with an ACII value.




## Type Cast 
 `char letter =  c`
```

 int total,n;
 double average;
 average = (double)total/n //total cast to double to ensure real division is used

 ```

 *Note : * Casting a floating-point number to an integer simply truncates the number (round down)




 ## Final Variables
A *final variable* or *user-defined constant* indentified by the keyword `final`, is a quantity whose value will not change.


`final double TAX_RATE = 0.08;`

- Constant indentifiers are, by convention, capitalized

- `final` variable can be declared without initializing immediatley.