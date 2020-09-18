# Reflection Katie Burgess

## Using a fenced code block, please display the correct output from running your program

```

Converting from Celsius to Fahrenheit!
35.00 degrees in Celsius is 95.00 degrees in Fahrenheit

```

## For each terminal window command, add an explanation to the following list

- `cd converter`: This command switches your current directory to converter.
- `poetry install`: This command installs all the required poetry dependencies for the lab or practical we are working on.
- `cd ..`: This command moves you back one directory.

## Please use one paragraph to explain the meaning of the following code segment

```
if __name__ == "__main__":
    typer.run(main)
```

When this code segment is run in the terminal window, typer.run(main) is performed, meaning that the typer will run the main function and perform the code inside of it. In this specific program, this code segment will then execute a conversion of either Celsius to Fahrenheit, Fahrenheit to Celsius, or another conversion through the third function.

## Please use one paragraph to explain the meaning of the following test case

```
def test_convert_celsius_to_fahrenheit_floating_point():
    """Check to ensure that Celsius to Fahrenheit conversion works."""
    temperature = 26.667
    converted_temperature = convert.convert_celsius_to_fahrenheit(temperature)
    assert converted_temperature == approx(80, rel=1e-3)
```

This test case tests the celsius to fahrenheit function. It sets the temperature to a tested value, and once the convert_celsius_to_fahrenheit() function is run, it asserts the correct value, allowing for a little room for different numbers in case the float rounds to a decimal number. If the assertion is equal to the converted temperature, it will return true, and if it is not equal it will return false and let you know that you have something to fix.

## What was the greatest technical challenge that you faced and how did you overcome it?

My greatest technical challenge I faced was trying to understand all the code. I have never seen an 'if __name__ == "__main__":' function in a program before as I've never worked as heavily in the terminal window as I do now. Also, through looking through the code on my own, trying to make sense of the class information in 'units.py' and the third converter function in'__main__.py'. It was challenging to try to make sense of it, but through time and looking back and forth between the files helped me have a deeper understanding of how the third function worked.

## After completing this assignment, what is task that you want to practice more? Why?

I want to practice making sense of code, being able to look at new code and understand what the programmer meant. I also want to get better at working with the terminal window. I feel a lot more capable with it already, but making the terminal window less intimidating to use will greatly increase my capabilities as a computer science student. I also want to practice using the software such as the delinter and the black poetry dependency, as they are still relatively new and I don't know exactly what they do yet.

## After completing this assignment, what is one experience for which you are grateful?

I am grateful for my experience working with GitHub. Through practicing in the labs and the practical today, I feel a lot more comfortable copying directories and using commands such as 'git add', 'git commit', and 'git push'. These experiences made the practical a lot easier than it would have been otherwise. By the end of the semester I feel like I will be very capable and confident in my GitHub skills.