## 0x04-pointers_arrays_strings

[0-reset_to_98.c](./0-reset_to_98.c)
```
98 Battery st.
Write a function that takes a pointer to an int as parameter and updates the
value it points to to 98.
```
* Prototype: void reset_to_98(int *n);

[1-swap.c](./1-swap.c)
```
Don't swap horses in crossing a stream
Write a function that swaps the values of two integers.
```
* Prototype: void swap_int(int *a, int *b);

[2-strlen.c](./2-strlen.c)
```
This report, by its very length, defends itself against the risk of being
read
Write a function that returns the length of a string.
```
* Prototype: int _strlen(char *s);

[3-puts.c](./3-puts.c)
```
I do not fear computers. I fear the lack of them
Write a function that prints a string, followed by a new line, to stdout.
```
* Prototype: void _puts(char *str);

[4-print_rev.c](./4-print_rev.c)
```
I can only go one way. I've not got a reverse gear
Write a function that prints a string, in reverse, followed by a new line.
```
* Prototype: void print_rev(char *s);

[5-rev_string.c](./5-rev_string.c)
```
A good engineer thinks in reverse and asks himself about the stylistic
consequences of the components and systems he proposes
```

[6-puts2.c](./6-puts2.c)

```
Half the lies they tell about me aren't true
Write a function that prints one char out of 2 of a string, followed by a new
line.
```
* Prototype: void puts2(char *str);
* The function should print only one character out of two, starting with the
  first one

[7-puts_half.c](./7-puts_half.c)
```
Winning is only half of it. Having fun is the other half
Write a function that prints half of a string, followed by a new line.
```
* Prototype: void puts_half(char *str);
* The function should print the second half of the string
* If the number of characters is odd, the function should print the
  (length_of_the_string - 1) / 2 last characters of the string

[8-print_array.c](./8-print_array.c)
```
Arrays are not pointers
Write a function that prints n elements of an array of integers,
followed by a new line.
```
* Prototype: void print_array(int *a, int n);
* where n is the number of elements of the array to be printed
* Numbers must be separated by comma, followed by a space
* The numbers should be displayed in the same order as they
  are stored in the array
* You are allowed to use printf

[9-strcpy.c](./9-strcpy.c)
```
Write a function that copies the string pointed to by src, including the
terminating null byte (\0), to the buffer pointed to by dest.
```
