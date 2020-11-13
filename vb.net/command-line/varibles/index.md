[« Go Back](..\creating-hello-world "Go Back")
<br/>

# Varibles, Assigning and Using them

Varibles are a simple way of storing data so it can be used again later in the program. You can store number, letters, binary, strings and anything you want really.

### Types Of Varibles

There are many types of varibles in Visual Basic but we will start with the basics.
Numbers and letters!

### Numbers (Integer)

In programming a whole number is also called an Integer, this is the name of the varible type you need to use when you declare it.
To declare a varile in Visual Basic you write the following. `Dim` is the decleration syntax for Visual Basic. `number` is the name of the varible, this can be any word. Numbers and spaces arent allowed. `Integer` is the type, this is very important and makes sure Visual Basic knows that the varible is.

```vb
Dim number As Integer
```

### Strings (String)

A string is a word or series of words or letters, basicaly a string can be any text you want it to be. They follow the same syntax as numbers but you need to change the type.

```vb
Dim word As String
```

### Using varibles

So to use a varible is very simple, you just type its name. So say we want to print the value of word we just do the following. As you can see its not in "". Enclosing something in "" will make it a string. We dont want that we want to use the value of word not print "word".

```vb
Console.WriteLine(word)
```

So lets run it! Ah...
Yea it doesnt work. Thats becuase we havent asigned the varible yet. We have created it but it has no value. So lets give it one
There are 2 ways to give a varible a value. We can either asign it when its created like bellow.

```vb
Dim word As String = "Hello There"
```

or we can asign it later.

```vb
word = "Hello There"
```

Here we dont need to declare its type of use `dim` as its already been declared earlier. We can just give it a value.
Now we can use it and print it to console. 
So lets try running it again.

```
Hello There
```

And there it is. We have managed to use a basic string varible. Here is the full program code if you got lost.

```vb
Module Program
    Sub Main(args As String())
        Dim word As String
        word = "Hello There"
        Console.WriteLine(word)
    End Sub
End Module
```

### So lets try numbers

Numbers work mostly the same however lets try doing some maths with them.
Lets declare 2 numbers.

```vb
Dim x As Integer = 10
Dim y As Integer = 5
```

There are many maths operators in Visual Basic but lets just start with `+` and `-`.
Using number varibles and doing maths with them is rather simple. Its just like algebra
Say we want to print the value of `x + y` we simply write:

```vb
Console.WriteLine(x + y)
```

If we want to subtract the 2 numbers then. You guessed it.

```vb
Console.WriteLine(x - y)
```

Here is the full code again that does both in one. (I know, its magic)

```vb
Module Program
    Sub Main(args As String())
        Dim x As Integer = 10
        Dim y As Integer = 5
        Console.WriteLine(x + y)
        Console.WriteLine(x - y)
    End Sub
End Module
```

Now lets use these varibles to make some decisions.

[» Next Page (next)](..\if-statements "Next Page")
