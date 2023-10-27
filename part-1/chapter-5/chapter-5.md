

# The Ruby Ecosystem


Chapter 6: Classes, Objects, and Modules
    Why Use Object Orientation?

    Object-Orientation Basics
        Local, Gloal, Obect, and lcass Variables
            Local Variables
            Global Variables
            Instance or Object Variables
            class Vaiables
        
        Class Methods versus Instance Methods
        Inheritance
        Overriding Existing Methods
        Reflection and discovering an Object's Methods
        Encapsulation
        Polymorphism
        Nested Classes
        The Scope of Constants

    Modules, Namespaces, and Mix-ins
        Namespaces
        
        Mix-ins
            Enumerable
            Comparable
            Using Mix-ins with Namespaces and Classes

        Building a Dungeon Text Adventure with Objects
            Dungeon Concepts
            Creating the Inital Classes
            Structs: Quick and Easy Data Classes
            Creating Rooms
            Making the Dungeon Work

        Summary


Chapter 7: Projects and Libraries

    Projects and Using Coe from Other Files
        Basic File Inclsion
        Inclsions from Other Directories
        Logic and Including Code
        Nested Inclusions
    
    Libraries
        The Standard Libraries
            net/http
            OpenStruct
        RubyGems
            Finding Gems
            installing a Simple Gem
            Using Gems
            Upgrading and Uninstalling Gems
            Creating Your Own Gems
        Bundler
    Summary

Chapter 8: Documentation, Error Handling, Debugging, and Testing

    Documentation
        Generating Documentation with RDoc
        RDoc Techniques

        Producing Documentation for an Entire Project
            Basic Formatting
        
        Modifiers and Options
            :nodoc: Modifier
            Turning RDoc Processing On and Off
            Command-Line Options
    
    Debugging and Errors
        Exceptions and Error Handling
            Rasing Exceptions
            Handling Exceptions
            handling Passed Exceptions
        Catch and Throw
        The Ruby Debugger
    Testing

    The Philosophy of Test-Driven Development
        Unit Testing
        More Minitest Assertions
    Benchmarking and Profiling
        Simple Benchmarking
        Profiling
    Summary

Chapter 9: Files and Databases
    Input and Output
        Keyboard Input

        File I/O
            Opening and Reading Files
            More File-reading Techniques
            Your Position Within a File
            Character Sets and Encodings
            Renaming and Delting Files
        
        File Operations
            Creating Filenames Platform-Independently
            Seeking
            Finding Ou When a File Was Last Modified
            Checking Whehter a File Exists
            Getting the Size of a File
            How to Know When You're at the End of a File

        Directories
            Navigating Throgh Directories
            Creating a Directory
            Deleting a Directory
            Creating Files in the Temporary Directory
    
    Basic Databases
        Text File Databases
            Reading and Searching CSV Data
            savind Data Back to the CSV File

        Storing Objects and Data Structures
            PStore
            YAML
    
    Relational Databases and SQL
        Relational Database Concepts
        MySQL, PostgreSQL, and SQLite
        Installing SQLite

        A Crash Course in Basic Database Operations and SQL
            What is SQL?
            CREATE TABLE
            INSERT INTO
            SELECT
            DELETE UPDATE
        Using SQLite with Ruby
        Connection to Other Database Systems
        ActiveRecord: A Sneak Peek
    
    Summary


Chapter 10: Distributing Ruby Code and Libraries
    Distributing Basic Ruby Programs
        The Shebang Line
        Associated File Types in Windows
    Detecting Ruby's Runtime Environment
        Easy OS Detection with RUBY_PLATFORM
        Environment Variables
        Accessing Command-Line Arguments
    Distrubting Ruby Libraries as Gems
        Createing a Gem
            Strucuting Your Files
            Creating a Specification File
            Building the Gem
            Easier Gem Creation
        Distributing a Gem
        RubyGems.org
    Depoying Ruby Applications as Remote Services
        CGI Scripts
            A Basic CGI Script
            Accepting CGI Variables
        Generic HTTP Servers
            WEBrick
    Summary

Chapter 11: Advanced Ruby Features