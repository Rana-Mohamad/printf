0x11. C - printf
---------------------------------
## Tasks:
0. I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life: Write a function that produces output according to a format.
	* Prototype: int _printf(const char *format, ...);
	* Returns: the number of characters printed (excluding the null byte used to end output to strings)
	* write output to stdout, the standard output stream
	* format is a character string. The format string is composed of zero or more directives. See man 3 printf for more detail. You need to handle the following conversion specifiers:
	* c
	* s
	* %
	* You don’t have to reproduce the buffer handling of the C library printf function
	* You don’t have to handle the flag characters
	* You don’t have to handle field width
	* You don’t have to handle precision
	* You don’t have to handle the length modifiers
1. Education is when you read the fine print. Experience is what you get if you don't: Handle the following conversion specifiers:
	* d
	* i
	* You don’t have to handle the flag characters
	* You don’t have to handle field width
	* You don’t have to handle precision
	* You don’t have to handle the length modifiers
2. With a face like mine, I do better in print: Handle the following custom conversion specifiers:
	* b: the unsigned int argument is converted to binary
3. What one has not experienced, one will never understand in print: Handle the following conversion specifiers:
	* u
	* o
	* x
	* X
	* You don’t have to handle the flag characters
	* You don’t have to handle field width
	* You don’t have to handle precision
	* You don’t have to handle the length modifiers
4. Nothing in fine print is ever good news: Use a local buffer of 1024 chars in order to call write as little as possible.
13. Print is the sharpest and the strongest weapon of our party: Handle the following custom conversion specifier:
	* r : prints the reversed string
14. The flood of print has turned reading into a process of gulping rather than savoring: Handle the following custom conversion specifier:
	* R: prints the rot13'ed string

