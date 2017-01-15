## __Unit 2 - ints, doubles, and Strings__

*Using numbers and words to do calculations, print text, and manipulate code.*

***

__ints__

- Numbers with no decimals (e.g. 7, 218, 43)

- Always round down towards zero (e.g. 7.7 = 7, 432.289 = 432)

- Available operations are +, -, *, /, %, etc.

```Java
int a = 24;
int b = 230;
int c = 9;

System.out.println(a / c); // PRINTS 2
```


__doubles__

- Number with decimal places (e.g. 7.728, 218.3, 43.925482)

- Available operations are +, -, *, /, %, etc.

```Java
double a = 24.25;
double b = 230;
double c = 9.4329;

System.out.println(a * b); // PRINTS 5577.5, sometimes adding extra random digits to end.
```

__Strings__

- Objects that hold world data; it can contain letters, numbers, and punctuation.

- Concatenate Strings with '+' symbol, between two String variables, or between two Strings surrounded by quotation marks.

- Available operations are '+' for concatenation.


```Java
String greeting = "Hello, my name is";
String name = "Luke";

System.out.println(greeting + " " + name); // PRINTS "Hello, my name is Luke"
```

__Mod - %__

- Returns the remainder of a number divided by another number.

```Java
int a = 25;
int b = 10;
int c = 300;

System.out.println(a % b); // PRINTS 5
System.out.println(c % a); // PRINTS 0
```

__Constants__

- Data objects that cannot be changed.

- Used to hold data that is always the same.

- Variable name capitalized to indicate it is a constant (not necessary, but preferred)

- Initiated at the root of the class.

```Java
public class welcome {
    public static final String WELCOME_MESSAGE = "Welcome to Google, "; // Added space for concatenation for later.
    public static final String AGE_DECLARATION = "I am ";

      public welcome(String name, int age) {
        this.name = name;
        this.age = age;
      }

      // ... rest of class here
}
```
