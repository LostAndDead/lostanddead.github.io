[« Go Back](..\if-statements "Go Back")
<br/>

# Select Statements

If statements with extra steps.
A select statement is like an if statement but it can decide between many outcomes based on the value of a varible. It takes just one value and choosed one of often many outcomes based on the value of the varible. It is much more efficient than just repeating if statements and is all round better.

### So lets make one

Say we have a program that needs to print something different depending on who is logging in. We could to a series of if statements for each user **or** we could use a select statement.

```vb
Dim user As String
user = "Cassie"
Select Case user
    Case "John"
        Console.WriteLine("Your meeting is starting in 30 mins")
    Case "Cassie"
        Console.WriteLine("Dont forget to check your email")
    Case "Tom"
        Console.WriteLine("Remember to hunt Jerry later")
    Case "Abby"
        Console.WriteLine("You have homework to submit later")
    Case Else
        Console.WriteLine("Unknown user")
End Select
```

We start once again by declaring the varible we want to use. And then comes the `Select Case` and after that we put the varible we want to test, this will be the varible that is used to compare to each statement and see if it matches or meets the criteria. We then declare the first `Case` and give it the value of "John", in this case if user is "John" then this code shall be ran. We then repeat this for all the users with there little message for each of them. At the end we have a `Case Else` this a a catch all for anything that doesnt meet the other criteria. We once again **must** end the select with `End Select`.

You can do many other values for comparison after `Case` such as numbers, `10 to 20` which will be true for all values 10 to 20. And many many other values can be used.

If we run the code above we can see that it prints the correct string for the correct user

```
Dont forget to check your email
```

And if we change user to "Tom" the output will change acordinly.

```
Remember to hunt Jerry later
```

Now that we are done with the basics of Visual Basic we can move onto the GUI elements and using the IDE more.

[» Next Page (Loops)](..\if-statements "Next Page")
