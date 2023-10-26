# Turning Ideas into Ruby Code


```js

let Section = {
    0: {
        title: "Turning Ideas into Ruby Code",
        page: 15
    },
    1: {
        title: "How Ruby Understands Concepts with Objects and Classes"
        page: 15
    }
    2: {
        title: "The Making of a Person",
        page: 16
    },
    3: {
        title: 'Basic Variables',
        page: 17
    },
    
   
}

```

### 0. Turning Ideas into Ruby Code

Part of the artistry of programming is being able to turn our ideas into computer programs

Once you become proficeint with a programming language, you can turn your ideas directly into code. However before yo can do this,
you need to see how ruby understand real-world concepts, and how you can relay your ideas into a form that Ruby appreciates.

### 1. How Ruby Understands Concepts with Objects and Classes

Ruby is an object-oriented programming language. In the simplest sense, this means that your Ruby programs can define and operate on concepts in a fashion that mimics how we might deal with concepts in the real world. Your program can contain concepts such as "people", "boxes", "tickets", "maps" or an other concepts you want to work with.


Object-oriented languages make it easy to implement these concepts in a wa that you can create objects based on them As an object-orented language, Ruby can then act on and understand the relationships between these concepts in a way you can define.


or example, you might want to create an application that can manage the booking of tickets for sports
events. The concepts involved include “events,” “people,” “tickets,” “venues,” and so forth. Ruby lets you put
these concepts directly into your programs, create object instances of them (instances of an “event” might
be the Super Bowl or the final of the 2018 World Cup), and perform operations on and define relationships
between them. With all these concepts in your program, you can quickly relate “events” to “venues” and
“tickets” to “people,” meaning that your code forms a logical system from the outset.

If you haven’t programmed much before, the idea of taking real-life concepts and using them directly in
a computer program might seem like an obvious way to make software development easier. However, object
orientation is a reasonably new idea in software development (the concept was developed in the 1960s, but
it only became popular in mainstream programming in the 1990s). With non–object-oriented languages,
the programmer has to take a more manual approach for handling concepts and the relationships between
them and while this adds more control, it also introduces extra complexity

### 2. The Making of a Person

```ruby

class Person
    attr_accessor :name, :age, :gender
end


```

 - class Person
 This line is where you start to define the concept of a person object. When de define concepts in Ruby we call them classes. A class is the definition of a single type of object. Class names in Ruby always start with a captial letter, so your programs will end up wth classes with nams ike User, Person, Place, Topic, Message, and so forth

 attr_accessor :name, :age, :gender

 The prceding line provides three attriutes for the Person class. An individual person has a name, an age, and a gender, and this line creates those atributes.

 attr stands for “attribute,” and accessor roughly
means “make these attributes accessible to be set and changed at will.”

 - end

 The end line denotes the end of a method or a block


 RECAP

 - A class defines a concept (such as a Person)
 - An object is a single thing based on a class

### 3. Basic Variables
