
<div class="container">

<h1>Intermediate Python – Loops with Data Structures</h1>

<p>
This documentation explains how Python loops work with different data structures:
<b>String, List, Tuple, Set, and Dictionary</b>.
Each section includes a definition and an example.
</p>

<h2>Topics Covered</h2>
<ul>
    <li>Loop with String</li>
    <li>Loop with List</li>
    <li>Loop with Tuple</li>
    <li>Loop with Set</li>
    <li>Loop with Dictionary</li>
</ul>

<hr>

<h2>Loop with String</h2>

<h3>Definition</h3>
<p>
A string is a sequence of characters. When a loop is used on a string,
Python accesses each character one by one.
</p>

<h3>Example</h3>
<pre><code>text = "Python"

for char in text:
    print(char)</code></pre>

P<br>
y<br>
t<br>
h<br>
o<br>
n<br>
<hr>

<h2>Loop with List</h2>

<h3>Definition</h3>
<p>
A list is an ordered collection of elements. Looping through a list allows
access to each element individually.
</p>

<h3>Example</h3>
<pre><code>numbers = [10, 20, 30, 40]

for num in numbers:
    print(num)</code></pre>
10<br>
20<br>
30<br>
40<br>
<hr>

<h2>Loop with Tuple</h2>

<h3>Definition</h3>
<p>
A tuple is similar to a list but immutable (cannot be changed).
Loops are used to read its elements.
</p>

<h3>Example</h3>
<pre><code>colors = ("red", "green", "blue")

for color in colors:
    print(color)</code></pre>
red<br>
green<br>
blue<br>
<hr>

<h2>Loop with Set</h2>

<h3>Definition</h3>
<p>
A set stores unique values and does not maintain a fixed order.
Looping through a set may return values in any order.
</p>

<h3>Example</h3>
<pre><code>fruits = {"apple", "banana", "cherry"}

for fruit in fruits:
    print(fruit)</code></pre>
banana<br>
apple<br>
cherry<br>
<hr>

<h2>Loop with Dictionary</h2>

<h3>Definition</h3>
<p>
A dictionary stores data in key–value pairs.
You can loop through keys, values, or both.
</p>

<h3>Loop through Keys</h3>
<pre><code>student = {"name": "John", "age": 21, "course": "Python"}

for key in student:
    print(key)</code></pre>
name<br>
age<br>
course<br>
<h3>Loop through Values</h3>
<pre><code>for value in student.values():
    print(value)</code></pre>
John<br>
21<br>
Python<br>
<h3>Loop through Keys and Values</h3>
<pre><code>for key, value in student.items():
    print(key, value)</code></pre>
name : John<br>
age : 21<br>
course : Python<br>
<hr>

</div>

</body>
</html>
