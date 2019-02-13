# Basic Loops
Scroll down to find references and explanations for different loop types; namely:
1. For Loop
2. While Loop

## 1. For Loop
```
for (int i = 0; i < 5; i++)
{
    print ("CUCUMBER!");
}
```
__What it does:__ It repeats something a set number of times per frame.
Here's how it works:

```
int i = 0;
```

1. It creates a variable. It only does this once.

```
i < 5;
```

2. It checks if the variable's current value has reached the value we specify (in this case; 5). If the value we specified has not been reached, it moves on to the next step.

```
i++;
```

3. Changes _i_ to track how many repeatitions have been done. This only happens if the value we specify has not been reached.

```
{
    print ("CUCUMBER!");
}
```

4. This is the end of a single repeatition, where it does what we tell it to between the curly braces. In this case, it prints out "CUCUMBER!" to the console.

It then does all this again but now starting from step 2. When does it stop doing this; when _i_ is not less than 5!

## 2. While Loop
```
int i = 0;

while (i < 5)
{
    print ("CUCUMBER!");
    i++;
}
```
__What it does:__ It repeats something while something is true.
