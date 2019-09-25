//Collection of notes in the C language

Scratch: Say (hello, world)

```C
printf("hello, world\n")
```

All printed words are called strings and stringa are enclosed by "string" <br>
\n tells computer to start a newline <br>
The ; is like the period at the end of a sentence. It tells the computer that this is the end of the statement.

Scratch: set counter to 0

```C
int counter = 0;
```

In C, you must declare the type of variable you are creating

Scratch: change counter by 1

```C
counter = counter + 1 # add any number to counter
counter +=1 # add any number to counter
counter++# only adds plus 1 to counter
```

The = sign is not "equals," it means "assign" or "get."

```C
if (x<y)
{printf("x is less than y/n");}
```

```C
if (x<y)
{printf("x is less than y\n");}
else if (x>y)
{print is greater than y\n");}
else if (x==y)
{printf("x is equal to y\n");}
```
Double equal sign used to represent equality

```C
While (true)
{printf("hello, world\n");}
```
The key word true never changes value

```C
for (int i=0; i<50; i++)
{printf("hello, world\n");}
```
Three inputs above are required to use for a loop

```C
answer=get_string("What's your name?\n");
printf("%s", answer);
```
Return value- what the function is handing back <br>
% is saying that it will give printf a string to put into the first input, the answer or variable

```C
string answer=get_string("What's your name?\n");
printf("hello, %s", answer);
```
