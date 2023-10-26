# Everything is an Object



### 0. Everything is an Object


### 1. Kernel Methods

Kernel is a special class (actually, a module -- more on this in Chapter 6) whose methods are made available in every class and scope throughout Ruby. You've used a key method proided by Kernel already, such as the puts method


However, in reality, puts is a method made
available from the Kernel module—a special type of class packed full of standard, commonly used methods,
making your code easier to read and write.

■ Note The Kernel module in Ruby has no relationship to kernels in operating systems or the Linux
kernel. As with a kernel and its operating system, the Kernel module is part of Ruby’s “core,” but there is no
connection beyond that. The word “kernel” is used merely in a traditional sense.


### 2. Passing Data to Methods

Let's create a very simple class that represents a dog:

```ruby

class Dog
    def bark(i)
        i.times do
            puts "Woof!"
        end
    end
end


# Multiple parameters may be specified
class Dog
    def say(, b, c)
        puts a
        puts b
        puts c
    end
end

my_dog = Dog.new
my_dog.say("Dogs", "can't", "talk!")

```

### 3. Using the Methods of the String Class

```
    puts "This is a test".length
    puts "This is a test".upcase
```

Ruby is capable of method chaining!

### 4. Using Ruby in a Non–Object-Oriented Style

So far in this chapter, we’ve looked at several reasonably complex concepts. With some programming
languages, object orientation is almost an afterthought, and beginners’ books for these languages don’t
cover object orientation until readers understand the basics of the language (particularly with Perl and
PHP, other popular web development languages). However, this doesn’t work for Ruby because Ruby is a
pure object-oriented language, and you can gain significant advantages over users of other languages by
understanding these concepts right away


n a language such as Perl or C, this method
would be called a procedure, function, or subfunction, as method is a word generally used to refer to an action
that can take place on an object. In Ruby, this method is still being defined on a class (the Object class), but
we can ignore that within this context.
After the method is defined—it’s still called a method, even though other languages would consider it to
be a subroutine or function—it becomes available to use immediately without using a class or object name,
like how puts is available without referring directly to the Kernel module. You call the method simply by
using its name on its own, as on the last line of the preceding example. Typing the preceding code into irb
results in the dog_barking method being called, giving the following result:
### 5. Summary