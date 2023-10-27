Chapter 3
# Numbers and Expressions


### 0. Numbers and Expressions

Let’s look at how you can use numbers in these ways in Ruby and
how to do something with them.

### 1. Basic Expressions

When programming, an expression is a combination of data (such as numbers or strings of text), operators
(such as + or -), and variables that, when understood by the computer, result in an answer of some form.
For example, these are all expressions:

Brackets (parentheses) work the same way as with regular arithmetic. Anything inside brackets is
calculated first (or, more technically, given higher precedence)



### 2. Variables
Variables are placeholders or
references to objects, including numbers, text, or any types of objects you’ve chosen to create. 

Be aware that you always need to initialize
variables (that is, assign a value to them) before using them, otherwise you will end up with an error.
```ruby

x = 10
puts x

```

mentions naming conventions in Ruby
They did not give an reserved words however


Variables are important because they allow you to write and use programs that perform operations on
varying data. For example, consider a small program that has the sole job of subtracting two numbers

```ruby

x = 100
y = 10
puts y - 10

```

If the code was written simply as puts 100 - 0, you'd get the same result, but its not as flexible. Using variables, you can get the values for x and y fromthe user, a file, or some other source. The only logic is the subtraction.

As variables are placeholders for values and data, they can also be assigned the results of an expression ( such as x = 2 - 1) and be used in expressions themselves ( such as x - y + 2). Here's a more complex example


```ruby

x = 50
y = x * 100
x += y
puts x

```

### 3. Comparison Operators and Expressions
```ruby

age = 10

def canUseSystem(input_age)
    puts "You're too young to use this system" if age < 18
end


def is_teenager(input_age)
    puts "You're NOT a teenager" unless age > 12 && age < 20
end

```

Comparison Meaning
x > y Greater than
x < y Less than
x == y Equal to
x >= y Greater than or equal to
x <= y Less than or equal to
x <=> y Comparison; returns 0 if x and y are equal, 1 if x is higher, and -1 if x is lower
x != y Not equal t


its possbile to group multiple expresions into a single expression, as with the following:

```ruby

    puts "You're a teenager" if age > 12 && age < 20

    # && is used to enforce that both age > 12 and age < 20
    # are true. However, you can also check whether one or
    # the other is true by using ||, as so:

    puts "You're either very oun or very old" if age > 80 || age < 10
```


### 4. Looping Through Numbers with Blocks and Iterators

```ruby

5.times do puts "Test" end

1.upto(5) { ...code to loop here... }
10.downto(5) { ...code to loop here... }
0.step(50, 5) { ...code to loop here... }


1.upto(5) { |number | puts number }
1.upto(5) { | i | puts i }



1.upto(5) do |number|
  puts number
end




```


### 5. Floating Point Numbers


```ruby

x = 10
y = 3
puts x.to_f / y.to_f

```
### 6. Constants

These unchanging values are called constants, and can also be
represented in Ruby by a variable name beginning with a capital letter:

Pi = 3.141592

(irb): warning: already initialized constant Pi



### 7. Text and Strings



String literals

puts "Hello, World

puts "Hello, World!".class

x = "Test"
y = "String"
puts "Success!" if x + y == "TestString"


x = %q{ This is a test of the mult
line capabilites {}}


### 8. String Expressions

puts "Success!" if "Test" + "String" == "TestString"

puts "abc" * 5


puts 120.chr -> 'x'
puts 97.chr # -> 'a'


### 9. Interpolation

x = 10
y = 20

puts "#{x} + #{y} = #{x + y}"

puts "100 * 5 = #{100 * 5}"

puts "#{x} + #{y} = #{x + y}"

x = "cat"

my_string = "It's a #{"bad " * 5} world"
puts my_string

x = 10
y = 20
puts x.to_s + " + " + y.to_s + " = " + (x + y).to_s
puts "#{x} + #{y} = #{x + y}"


### 10. String Methods
capitalize
.downcase
.chop
.next
.reverse
.sum
.swapcase
.upcase
.upcase.reverse
.upcase.reverse.next

puts "This is a test".length


### 11. Regular Expressions and String Manipulation


puts "foobar".sub('bar', 'foo')
puts "I am Desmond".sub("Desmond", "BATMAN!")

puts "this is a test".gsub('i', '')

puts "this is a test".gsub('i', '')

x = "This is a test"
puts x.sub(/^../, 'Hello')


