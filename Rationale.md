# Introduction Rationale

### Which approach was easier, why?
I found the OOP Aproach easier because there was less to define in terms of certain things, I also didnt have to create 3 seperate lists and only had to initialise one item with its three set params, then print it with an object method. while with the procedural approach, I needed to define 3 seperate lists and loop through all of them. Which is objectively longer of a process.

EX:\
Procedural:
```
list = ["1", "2", "3"]
list2 = ["4", "5", "6"]
for i in range(len(list)):
	print(list[i], list2[i])
```

Class:
```
#Items Class
class Items:
	def __init__(self, item, item2):
		self.item = item
 		self.item2 = item2

	def print_(self):
 		print(self.item, self.item2)

items = Items("1", "4")
items.print_()
```

While there may be more lines of code, the class approach is more efficient in terms of run-time.

##

### Which one took the least amount of setup?
In my opinion, the class based one took less setup because I didnt need to set up a bunch of lists with values that I needed to type out individually into the list first. With the class, I was able to create multiple objects with a few lines of code, and I didnt have to loop through anything because it was already defined within the instance of the item and doesnt need to get the correct index.

##

### Which Would Be More Efficient if you had 100 items?
I believe the more efficient process would be object oriented, because instead of having to loop through a list of 100 items, a class only has to call the name those items are defined as in the code. This is a much faster process because it doesnt use an iterative sequence to gather all of the list items.

##

### What are the differences between OOP and Procedural
<br>
<p align="center">Comparison between Procedural and Object Oriented</p>
<table>
	<tr>
		<th>Procedural</th>
		<th>Object Oriented</th>
	</tr>
	<tr>
		<td>Procedural is split up into portions called "Functions"</td>
		<td>Object Oriented is split into portions called "Objects"</td>
	</tr>
	<tr>
		<td>Procedural makes it harder to add data to functions</td>
		<td>Object oriented makes it so you can easily add new data and functions</td>
	</tr>
	<tr>
		<td>Procedural does not give a proper way to hide variables and data, making in insecure.</td>
		<td>Object Oriented gives a proper to hide variables and data, making it secure.</td>
	</tr>
	<tr>
		<td>Procedural is unrealistic, and based on the Unreal-World</td>
		<td>Object Oriented is realistic, and bends more towards Real-World scenarios.</td>
	</tr>
	<tr>
		<td>Procedural uses the concept of procedure abstraction</td>
		<td>Object Oriented uses the concept of data abstraction</td>
	</tr>
</table>

<p align="center">Pros and Cons of Procedural</p>
<p>Pros</p>
<ul>
	<li>Good for general-purpose programs</li>
	<li>Simple and straight forward</li>
	<li>Less taxing on memory</li>
</ul>
<p>Cons</p>
<ul>
	<li>Prioritising Operations over data</li>
	<li>Lacks code reusablity</li>
	<li>Hard to relate to real-world objects</li>
</ul>
<p align="center">Pros and Cons of Object Oriented</p>
<p>Pros</p>
<ul>
	<li>Prioritises data over operations</li>
	<li>Able to reuse code</li>
	<li>Easy to relate to real world objects</li>
</ul>
<p>Cons</p>
<ul>
	<li>Steep Learning Curve</li>
	<li>More difficult to use for general-purpose programs</li>
	<li>Larger program size, which can be taxing on memory</li>
</ul>