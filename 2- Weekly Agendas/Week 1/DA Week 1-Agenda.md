<h1><strong><span style="color: #77C8D5;">Data Analysis Week 1 Agenda</strong></span>

![logo](https://github.com/clarusway/DS-EU-1523-DA-Module/blob/main/2-%20Weekly%20Agendas/teamwork_logo.png)
 
<h2>
<br> 
<br>

<h1><strong><span style="color: #3498DB;">Meeting Agenda</strong></h1></span>

<span class="c16 c30">▶ </span><span
class="c42 c82">Icebreaking (5m)</span><span class="c16 c23"> </span>


<span class="c16 c30">▶ </span><span
class="c42 c82">Questions & Problems Related to Course Topics (30m)</span><span class="c46 c42 c48"> </span>

<span class="c30">▶ </span><span class="c46 c48 c42">Interview Questions (15m)</span>

<span class="c30">▶ </span><span class="c46 c48 c42">Additional Resources / Project Discussion (30m)</span>

<span class="c30">▶ </span><span class="c46 c48 c42">Video of the Week (5m)</span>

<span class="c30">▶ </span><span class="c46 c48 c42">Retro Meeting on a personal and team level (5m)</span>
<br>
<br>
<br>

<div style="page-break-after: always;"></div>

<h1><strong><span style="color: #3498DB;">Teamwork Schedule</strong></h1></span>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Ice-breaking</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                </tr>
</table>

- Personal Questions (Study Environment, Kids etc.) 
- Any challenges (Classes, Coding, studying, etc.) 
- How you’re studying, you need personal advice? 
- Remember that practice makes perfect. 
- What exactly each student does for the team, if they know each other, if they care for each other, if they follow and talk with each other etc. 
- Remind that practice makes perfect.

<br>
<br>


 <hr>
<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Questions & Problems Related to Course Topics</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>30m</p><td>                </tr>
</table>

<h3>

- [Python Basics: Chapter 06 – Functions and Loops](https://realpython.com/quizzes/pybasics-functions-loops/viewer/)

- [Quiz about Python Lambda Functions](https://realpython.com/quizzes/python-lambda/viewer/)

- [Python Lambda - Exercises, Practice, Solution](https://www.w3resource.com/python-exercises/lambda/index.php)

- **Solve the following questions in a team collaboration.**
<br><br>

**1. What will be the output of the following Python code?**

```bash
def printMax(a, b):
    if a > b:
        print(a, 'is maximum')
    elif a == b:
        print(a, 'is equal to', b)
    else:
        print(b, 'is maximum')
printMax(3, 4)
```
<strong>A.</strong>  3<br>
<strong>B.</strong> 4<br>
<strong>C.</strong>  4 is maximum<br>
<strong>D.</strong> 3 is maximum


<br>

**2. What is the output of the following program?**

```bash
x = 50
def func(x):
    print('x is', x)
    x = 2
    print('Changed local x to', x)
func(x)
print('x is now', x)
```

<strong>A.

```bash
x is 50
Changed local x to 2
x is now 50
```

<strong>B.

```bash
x is 50
Changed local x to 2
x is now 2
```

<strong>C.

```bash
x is 50
Changed local x to 2
x is now 100
```
<strong>D.</strong> None of the mentioned


<br>

**3. What will be the output of the following Python code snippet?**

```bash
def function1(var1=5, var2=7):
    var2=9
    var1=3
    print (var1, " ", var2)
function1(10,12)
```

<strong>A.</strong> 5 7<br>
<strong>B.</strong>  3 9<br>
<strong>C.</strong>  10 12<br>
<strong>D.</strong>  error
<br>


<br>

**4. What is called when a function is defined inside a class?**

<strong>A.</strong> Module<br>
<strong>B.</strong>  Method<br>
<strong>C.</strong>  Class <br>
<strong>D.</strong>  Another function
<br>


<br>

**5. What is the purpose of the “def” keyword in Python?**

<strong>A.</strong>  It is slang that means "the following code is really cool"<br>
<strong>B.</strong>  It indicates the start of a function<br>
<strong>C.</strong>  It indicates that the following indented section of code is to be stored for later<br>
<strong>D.</strong>    b and c are both true
<br>


<br>


**6. What will be the output of the following Python code?**

```bash
def san(x):
    print(x+1)
x=-2
x=4
san(12)
```
<strong>A.</strong> 13<br>
<strong>B.</strong> 10<br>
<strong>C.</strong> 2<br>
<strong>D.</strong> 5


<br>

**7. What is the output of the following program?**

```bash
def foo(fname, val):
    print(fname(val))
foo(max, [1, 2, 3])
foo(min, [1, 2, 3])
```

<strong>A.

```bash
3
1
```

<strong>B.

```bash
1
3
```

<strong>C.

```bash
1
1
```
<strong>D.

```bash
3
2
```


<br>

**8. What will be the output of the following Python code snippet?**


```bash
f=lambda x:bool(x%2)
print(f(20), f(21))
```

<strong>A.</strong>  False True<br>
<strong>B.</strong>  False False<br>
<strong>C.</strong>  True True<br>
<strong>D.</strong>     True False
<br>


<br>

**9. What will be the output of the following Python code?**

```bash
random.randrange(0,91,5)
```
<strong>A.</strong> 10<br>
<strong>B.</strong> 18<br>
<strong>C.</strong> 79<br>
<strong>D.</strong> 95


<br>

**10. What is the output of the following program?**

```bash
def foo():
    try:
        return 1
    finally:
        return 2
k = foo()
print(k)
```
<strong>A.</strong> 8<br>
<strong>B.</strong> 6<br>
<strong>C.</strong> 4<br>
<strong>D.</strong> 2


<br>


**11. What will be the output of the following Python code?**

```bash
def f(x, y, z): return x + y + z
print(f(2, 30, 400))
```
<strong>A.</strong> 431<br>
<strong>B.</strong> 432<br>
<strong>C.</strong> 230400<br>
<strong>D.</strong> 2212


**12. What will be the output of the following Python code?**

```bash
print({a**2 for a in range(4)})
```
<strong>A.</strong> {1, 4, 9, 16}<br>
<strong>B.</strong>  {0, 1, 4, 9, 16}<br>
<strong>C.</strong> {0, 1, 4, 9}<br>
<strong>D.</strong> Error


<br>

**13.  What will be the output of the following Python code?**

```bash
a=[1,2,3,4]
b=[sum(a[0:x+1]) for x in range(0,len(a))]
print(b)
```
<strong>A.</strong>  10<br>
<strong>B.</strong>   [1,3,5,7]<br>
<strong>C.</strong> [1,3,6,10]<br>
<strong>D.</strong>  8


<b>

<b>
<b>

</h4>
 
 <br>

 <hr>
<br>
<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Interview Questions</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>15m</p><td>                </tr>
</table>

**1. Explain Python Functions?**

**2.  What is Python's parameter passing mechanism?**

**3.  What is the difference between remove() function and del statement?**

**4.  What is the use of break statement?**

**5.  What are the different types of operators in Python?**

**6.  What is a generator in Python?**

<hr>

<br>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Additional Resources / Project Discussion</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>25m</p><td>                </tr>
                
</table>

- **Read and review the articles in the links below.**

1- [Lambda Functions with Practical Examples in Python](https://towardsdatascience.com/lambda-functions-with-practical-examples-in-python-45934f3653a8)

2- [How the Python Lambda Function Works – Explained with Examples](https://www.freecodecamp.org/news/python-lambda-function-explained/)

3- [Applying Lambda functions to Pandas Dataframe](https://www.javatpoint.com/applying-lambda-functions-to-pandas-dataframe)
<br><br>
- **Attempt to solve the questions in the following workshop notebooks on your own. It is not important whether you reach a solution or not. We encourage you to challenge yourself by thinking in Python for the solution.**

[Workshop-1 (Prep DAwPy)](https://github.com/clarusway/DS-EU-1523-DA-Module/blob/main/2-%20Weekly%20Agendas/Week%201/Workshop-1%20(Prep%20DAwPy).ipynb)

[Workshop-2 (Prep DAwPy)](https://github.com/clarusway/DS-EU-1523-DA-Module/blob/main/2-%20Weekly%20Agendas/Week%201/Workshop-2%20(Prep%20DAwPy).ipynb)

<br>
<hr>

<table style= "width:100%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Video of the Week</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>10m</p><td>                </tr>
</table>

- [Python Lambda Functions](https://www.youtube.com/watch?v=KR22jigJLok)
 <br><br>

<hr>
<br>
<table style= "width:97%;">
                <tr>
                <td style="color: #FA8072; text-align:left "><h3><strong><p>Retro Meeting on a personal and team level</td>
                <td style="color: #FA8072; text-align:right;"><h3><strong><p>5m</p><td>                </tr>
</table>



Ask the questions below:

- What went well? 
- What could be improved? 
- What will we commit to do better in the next week?
<br><br>
<hr>
