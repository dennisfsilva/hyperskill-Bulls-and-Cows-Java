# Bulls and Cows
[Bulls and Cows](https://hyperskill.org/projects/53) provides a comprehensive overview of how to perform various tasks related to integer arithmetic, generate random numbers, store data in data structures, and handle errors.


Code sample:

```
Input the length of the secret code:
> 6
Input the number of possible symbols in the code:
> 5
Error: it's not possible to generate a code with a length of 6 with 5 unique symbols.

Input the length of the secret code:
> abc 0 -7
Error: "abc 0 -7" isn't a valid number.

Input the length of the secret code:
> 6
Input the number of possible symbols in the code:
> 37
Error: maximum number of possible symbols in the code is 36 (0-9, a-z).

Input the length of the secret code:
> 4
Input the number of possible symbols in the code:
> 12
The secret is prepared: **** (0-9, a-b).
Okay, let's start a game!
Turn 1:
> a234
Grade: 1 bull and 1 cow
Turn 2:
> 73b4
Grade: 2 bulls and 1 cow
Turn 3:
> 9374
Grade: 4 bulls
Congratulations! You guessed the secret code.
```
