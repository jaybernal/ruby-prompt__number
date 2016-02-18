---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

Fixnum (Integer) and Floats (numbers with decimals)

# What are some common operations and comparisons you would perform on numbers?

+ - * / % **
 == <= >= < > != <=>

# What is the difference between the `+` operation on a number versus on a String?

when using the '+' sign on numbers it will add the value ie. 5 + 5 = 10
when using the '+' sign with strings it will join strings togehter ie. 'hello' + 'jay' = 'hello jay'

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

'20'.to_i + 2 = 22

# What is the purpose of the `times` operation? Is that the same as `*`?

The times method provides an alternative to the 'for' loop. The times method allows a specific number of times to pass through the block.
for example
5.times{|i| puts "jay"}
