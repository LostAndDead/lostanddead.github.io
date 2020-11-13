[« Go Back](..\varibles "Go Back")
<br/>

# If Statements

If statements are a way of making a this or that decision based on the result of a comparison or statement. This can be used to alter the flow of your program based on user input or varibles.

**Quick Stop For Booleans**

Booleans are another varible type that is often used by if statements, its a simple `True` or `False` value, cant be anything else. All if statements resolve in the end to a Boolean.

### The basics

Lets start with a basic if statement. Say we have number `x`, if `x` is greater than 10 we want to do one thing, if its not, do something else. Simple right. Well yes it is.

```vb
Dim x As Integer
x = 15
If (x > 10) Then
    Console.WriteLine("Greater Than 10")
Else
    Console.WriteLine("Less Than 10")
End If
```

So first we declare `x` (the varible we want to test) and we asign it a value.
Then we start the If statement. We start it with `If` and then we open the comparison with `(` here we can type the comparison we want to evaluate in this case we just use `x > 10` this means if the value of x is greater than 10 we run the code in the `If` statement, if it isnt we run the code in the `Else`. We need to close the comparison with `)` and then we open the area for the statement with `Then` after this follows the code we run if its true. Here we just print "Greater Than 10" then we define the `Else`, this isnt required, you can have `If` without `Else` but in this case we want it. Then we can give it the code we want it to run if the statement isnt true. In this case we just print "Less Than 10". We then **need** to close the statement with `End If`. This tells the program we are done with this statement and are ready to move on.
So if we run this with the value of 15 as it is above we will get the following output:

```
Greater Than 10
```

We get this as well duh, 15 is greater than 10. If we change x to say 5 we will get the following:

```
Less Than 10
```

As again duh, 5 is less than 10


[» Next Page (Select Statements)](..\select-statements "Next Page")
