---
layout: base
title: notes for ap csp
permalink: /notes/
---
these are some notes

###Lists and dictionaries

Lists and Dictionaries can collect information. 
You can add stuff to lists with .append(expression)

for_loop
this is a loop that pulls data out of a list
def for_loop():
    print("For loop output\n")
    for record in InfoDb:
        print_data(record)

while_loop
iterates through stuff similarily to for_loop, but this time it only iterates through a set amount
 while loop algorithm contains an initial n and an index incrementing statement (n += 1)
def while_loop():
    print("While loop output\n")
    i = 0
    while i < len(InfoDb):
        record = InfoDb[i]
        print_data(record)
        i += 1
    return

while_loop()

recursive loop
this loops through itself by calling itself repeatedly.
def recursive_loop(i):
    if i < len(InfoDb):
        record = InfoDb[i]
        print_data(record)
        recursive_loop(i + 1)
    return
    
print("Recursive loop output\n")
recursive_loop(0)


HTML

