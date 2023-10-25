# Baby Steps

```js

let Section = {
    0: {
        title: "Baby Steps",
        page: 11
    },
    1: {
        title: "irb: Interactive Ruby",
        page: 12
    },
    2: {
        title: 'Ruby is "English" for Computers"',
        page: 12
    },
    3: {
        title: "Why Ruby Makes a Great Programming Language",
        page: 13
    },
    4: {
        title: "Trails for the Mind",
        page: 14
    }
}

```

Recap of chapter 1

In Chapter 1, you focused on instaling Ruby
at the end you loaded a program called irb



### 1. irb: Interactive Ruby

irb stands for "Interactive Ruby"

1 + 1


f you want to experiment further, try other arithmetic such as 100 * 5, 57 + 99, 10 – 50, or 100 / 10

User Defined Note
Take note that ruby does not coerce integers to floating point values, they are "floored". Given that both values are integers

For example:

2 / 3 = 0

However if an argument is a floating point value then all other values of the expression will be coerced into floating point values


### 2. Ruby Is "English for Computers"

Compares and contracts natural language to computer language,

natural langauges would make bag programming langugages due to ambiguity and complexity


### 3. Why Ruby Makes a Great Programming Language


Ruby doesn't use semi-colons


```ruby

user = User.find_by_email('me@privacy.net')
user.country = 'Belgium'

```

### 4. Trails for the Mind

Throughout the book, I’ll ask you to try out different blocks of code and to play with them to see if
you get the results you want. You’ll occasionally surprise yourself and sometimes chase your code into dead
ends; this is all part of the fun. Whatever happens, all good programmers learn from experimentation, and
you can only master a language and programming concepts by experimenting as you go along.

Logically, print "test" results in test being printed to the screen. However, the => nil suffix is the
result of your code as an expression (more about these in Chapter 3). This appears because all lines of code
in Ruby are made up of expressions that return values. 

```print "2+3 is equal to " + 2 + 3```


```ruby
TypeError: no implicit conversion of Fixnum into String
from (irb):45:in `+'
from (irb):45
from :0
```



### End of Baby Steps