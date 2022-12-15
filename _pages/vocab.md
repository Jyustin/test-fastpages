---
layout: page
title: vocab for ap csp
permalink: /vocab/
---


|   basic vocab terms    |                                                 definition                                                 |
|:----------------------:|:----------------------------------------------------------------------------------------------------------:|
| list                   | data type that can have data appended to it with .append(expression).                                      |
| dictionary             | data type that stores data in key:value pairs                                                              |
| selection              | decision or question an algorithm may reach, in which case the algorithm now has options.                  |
| Algorithm              | A process or set of rules to be followed in calculations or other problem solving operations.              |
| iteration              | when something is repeated. usually done using loops. REPEAT N TIMES is pseudocode for this.               |
| conditional statements | when the code acts based on different conditions based on user input or stored data.                       |
| NESTED CONDITIONAL     | conditional statement in a conditional statement                                                           |
| Sequencing             | when you do certain steps in order, for example, doing the first step then the second then the third, etc. |
| Selection              | when the programmer decides between two different outcomes.                                                |
| variable               | a way of storing information in a computer program, which could later be changed, referenced, and used     |
| objects                | a structure that can take on a data-type value                                                             |
|  Concatenation         |when you add strings or integers together. can't add strings and integers                                   |
|  Hexadecimal           | numbering system from 1-16. 1-9 are numbers and 9-16 go from a-f                                           |
|  bits                  | A binary digit, either 0 or 1                                                                              |
|  bytes                 | group of binary digits operating as a unit                                                                 |
|  floating point        | positive or negative numbers that can include decimals                                                     |
| .upper                 | simply makes a string uppercase                                                                            |
| .lower                 | changes string to lowercase                                                                                |
| RGB                    | a mix of colors using binary. (x, y, z) determines color, x is red, y is green, z is blue. 0 is dark       |




# code vocab

### if, else, and elif statements

an if statement will run a set of code if a certain requirement is met. adding else will mean another piece of code runs if the requirement is not met.

lastly, elif means that if that first condition is not met but the other is, that code in the elif will run. 

code example below 

``if (time < 10) {
  greeting = "Good morning";
} else if (time < 20) {
  greeting = "Good day";
} else {
  greeting = "Good evening";
}``

### nested statements

a nested statement will just be that statement within the same statement. 

example:

if a = 2:
    if b = 3:
        print("ok")
        this would be a nested if statement as it is an if statement in an if statement

### for and while loops

these are loops that iterate through something or keep something running

``i = 1
while i < 6:
  print(i)
  i += 1``

``fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)``

``for x in range(2, 6):
  print(x)``
this one uses range, printing all numbers from 2 to 5


### Boolean expression    

statements that can be true or false

``a = 200
b = 33

if b > a:
  print("b is greater than a")
else:
  print("b is not greater than a")``

  this is boolean expression because the 2 outputs are true or false.

  ### simple concatenation ex:

``a = 1
b = 2
print(a + b)``
plus sign is concatenation

### truth tables 

truth tables essentially can be used to simplify code and show what the outputs for things can be

| x | y | x & y |
|---|---|-------|
| t | t | t     |
| t | f | f     |
| f | t | f     |
| f | f | f     |

example

