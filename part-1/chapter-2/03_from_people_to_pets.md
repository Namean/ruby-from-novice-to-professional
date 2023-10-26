# From People to Pets




### 0. From People to Pets

You started out with a Person class, but now you need something a bit more complex, so let’s create
some “pets” to live inside Ruby. You’ll create some cats, dogs, and snakes. The first step is to define the
classes. You could do something like this:


```ruby 
class Cat
    attr_accessor :name, :age, :gender, :color
end

class Dog
    attr_accessor :name, :age, :gender, :color
end

class Snake
    attr_accessor :name, :age, :gender, :color
end
```

It’s just like creating the Person class, but multiplied for the three different animals. You could continue
by creating animals with code such as lassie = Dog.new or sammy = Snake.new and setting the attributes
for the pets with code such as lassie.age = 12 or sammy.color = "Green". 


However, creating the classes in this way would miss out on one of the more interesting features of
object-oriented programming: inheritance.
Inheritance allows different classes to relate to one another and group concepts by their similarities. In
this case, cats, dogs, and snakes are all pets. Inheritance allows you to create a “parent” Pet class, and then
let your Cat , Dog , and Snake classes inherit (“is-a”) the features that all pets have.


Almost everything in real life exists in a similar structure to your classes. Cats can be pets, which are, in
turn, animals; which are, in turn, living things; which are, in turn, objects that exist in the universe. A hierarchy
of classes exists everywhere, and object-oriented languages let you define those relationships in code


### 1. Structuring Your Pets Logically



### Controlling Your Pets


###