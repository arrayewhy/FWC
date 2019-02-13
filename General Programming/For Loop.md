# For Loop

```
for (int i = 0; i < 5; i++)
{
    print ("CUCUMBER!");
}
```

What it does: It repeats something a set number of times per frame.

# How it works:

1. It starts when we call it with its preset format.

```
for ()
```

2. It creates a variable. It only does this once.

```
int i = 0;
```

3. It checks if the variable's current value has reached the value we specify (in this case; `5`). If the value we specified has not been reached, it moves on to the next step.

```
i < 5;
```

4. Changes `i` to track how many repetitions have been done. This only happens if the value we specify has not been reached.

```
i++;
```

5. This is the end of a single repetition, where it does what we tell it to between the curly braces. In this case, it prints out "CUCUMBER!" to the console.

```
{
    print ("CUCUMBER!");
}
```

It then does all this again but now starting from step 3. When does it stop doing this; when `i` is not less than `5`!
