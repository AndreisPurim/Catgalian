# *Catgalian*: Programming C in Latgalian
## Overview
*Catgalian* (C plus Latgalian) is an esolang/joke programming language inspired by the Latgalian dialect¹ based on Mini-C. It is not suppose to be taken seriously, so have fun.

**Disclaimer 1:** I don't speak Latgalian at all, so feel free to make corrections. Also, feel free to contribute to the code or language.
**Disclaimer 2:** For now, the best I have is a silly "compiler" that transforms the *catgalian* input into javascript and runs *eval()* to see the output in the website. It took around 30 minutes to make so it is not supposed to be serious. But I do plan on actually explaining catgalian into a fully functional language in some nearby future!

## Keywords
### Control Structures
-   **`ja`**: if statement.  `ja (x > 0) { drukāt("Pozitīvs"); }` 
-   **`citādi`**: else statement. `ja (x > 0) { drukāt("Pozitīvs"); } citādi { drukāt("Negatīvs"); }` 
-   **`kamēr`**: while loop. `kamēr (i < 10) { drukāt(i); i++; }` 
-   **`par`**: for loop.  `par (i = 0; i < 10; i++) { drukāt(i); }` 

### Functions
-   **`funkcija`**: Declares a function.    `funkcija skaitīt(a, b) { atgriezt a + b; }` 
-   **`atgriezt`**: Returns a value from a function.

### Data Types
-   **`vesels`**: `number`
-   **`peld`**: `number` (floating-point)
-   **`burts`**: `string`
-   **`tukšs`**: `void`

### Variable Declarations
-   **`statisk`**: Mutable variable. `statisk x = 10;` 
-   **`pastāvīg`**: Constant variable.    `pastāvīg PI = 3.14;` 

### Input/Output
-   **`drukāt`**: Outputs text.  `drukāt("Sveiki!");` 
-   **`lasīt`**: Reads user input.   `vesels vecums = lasīt("Ievadi vecumu:");` 
    
### Operators
-   Logical: `&&`, `||`, `!`
-   Arithmetic: `+`, `-`, `*`, `/`, `%`
-   Comparison: `==`, `!=`, `<`, `>`, `<=`, `>=`

