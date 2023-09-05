*C _ malloc, free

*TASKS

*[0. Float like a butterfly, sting like a bee](0_create_array.c)

_ Write a function that creates an array of chars, and initializes it with a specific char.

_ Prototype: char *create_array(unsigned int size, char c);
_ Returns NULL if size = 0
_ Returns a pointer to the array, or NULL if it fails

*[1. The woman who has no imagination has no wings](1_strdup.c)

_ Write a function that returns a pointer to a newly allocated space in memory, which contains a copy of the string given as a parameter.

_ Prototype: char *_strdup(char *str);
_ The _strdup() function returns a pointer to a new string which is a duplicate of the string str. Memory for the new string is obtained with malloc, and can be freed with free.
_ Returns NULL if str = NULL
_ On success, the _strdup function returns a pointer to the duplicated string. It returns NULL if insufficient memory was available

* [2. He who is not courageous enough to take risks will accomplish nothing in life](2_str_concat.c)

_ Write a function that concatenates two strings.

_ Prototype: char str_concat(char s1, char s2);
_ The returned pointer should point to a newly allocated space in memory which contains the contents of s1, followed by the contents of s2, and null terminated
if NULL is passed, treat it as an empty string
_ The function should return NULL on failure

*[3. If you even dream of beating me you'd better wake up and apologize](3_alloc_grid.c)

_ Write a function that returns a pointer to a 2 dimensional array of integers.

_ Prototype: int **alloc_grid(int width, int height);
_ Each element of the grid should be initialized to 0
_ The function should return NULL on failure
_ If width or height is 0 or negative, return NULL

*[4. It's not bragging if you can back it up](4_free_grid.c)

Write a function that frees a 2 dimensional grid previously created by your alloc_grid function.

Prototype: void free_grid(int **grid, int height);
Note that we will compile with your alloc_grid.c file. Make sure it compiles.

*[5. It isn't the mountains ahead to climb that wear you out; it's the pebble in your shoe](100_argstostr.c)

_ Write a function that concatenates all the arguments of your program.

_ Prototype: char *argstostr(int ac, char **av);
_ Returns NULL if ac == 0 or av == NULL
_ Returns a pointer to a new string, or NULL if it fails
_ Each argument should be followed by a \n in the new string  

*[6. I will show you how great I am] (101_strtow.c)

_ Write a function that splits a string into words.

_ Prototype: char **strtow(char *str);
_ The function returns a pointer to an array of strings (words)
_ Each element of this array should contain a single word, null_terminated
_ The last element of the returned array should be NULL
_ Words are separated by spaces
_ Returns NULL if str == NULL or str == ""
_ If your function fails, it should return NULL

