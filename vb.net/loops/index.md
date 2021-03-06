[« Go Back](..\select-statements "Go Back")
<br/>

# Loops <!-- omit in toc -->

Loops are a way of repeating specific bits of code until a condition is met or it has been run enough times. There are many types of loops in Visual Basic, we will go over each of them separately.

- [While](#while)
- [For](#for)
- [For Each](#for-each)
- [Do](#do)
- [Nested Loops](#nested-loops)

## While

These loops will keep repeating an area of code along as the condition is met is will check this condition every time it gets to the end of the sequence. This can be useful for a variety of things, however most things this loop is useful for can be done better with another loop. But its always good to know as it can have its uses.

```vb
Dim x As Integer
x = 1
While (x < 10)
    Console.WriteLine(x)
    x += 1
End While
```

This simple bit of code starts with the value of one, it then checks if the value is less than 10, if it is it prints it and then adds 1 to it, it then checks again and keeps doing this until the condition fails causing the program to end. Running this we should get all the numbers from 1 to 9.

```
1
2
3
4
5
6
7
8
9
```

And we do,
Now try writing this again to print all the numbers from 7 to 25. The answer is hidden below, be sure to give it a try before you check the answer. It isn't as hard as you may thing.

<details>
<summary>Click Me To Show Answer</summary>
<p>
<br/>
Here is the working code. There are others that would work but this for sure does.
<!--Yea i know this is jank af, it is the only way i can get it to format in the drop down-->
<pre class="highlight"><code><span class="k">Dim</span> <span class="nv">x</span> <span class="ow">As</span> <span class="kt">Integer</span>
<span class="n">x</span> <span class="o">=</span> <span class="mi">7</span>
<span class="k">While</span> <span class="p">(</span><span class="n">x</span> <span class="o">&lt;</span> <span class="mi">26</span><span class="p">)</span>
    <span class="nb">Console</span><span class="p">.</span><span class="n">WriteLine</span><span class="p">(</span><span class="n">x</span><span class="p">)</span>
    <span class="n">x</span> <span class="o">+=</span> <span class="mi">1</span>
<span class="k">End</span> <span class="k">While</span>
</code></pre>
</p>
</details>  
<br/>

## For

## For Each

## Do

## Nested Loops

[» Next Page (Loops)](..\loops "Next Page")



