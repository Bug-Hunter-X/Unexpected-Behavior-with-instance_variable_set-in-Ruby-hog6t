# Ruby: Unexpected Behavior with instance_variable_set

This example demonstrates a potential issue when using `instance_variable_set` in Ruby. Directly manipulating instance variables can bypass the class's methods, potentially leading to unexpected behavior and making code harder to maintain.

The `bug.rb` file shows how modifying an instance variable using `instance_variable_set` can alter the object's state in a way that might not be reflected in the class's defined methods, potentially leading to inconsistencies.

The `bugSolution.rb` file suggests better practices for handling object state modifications within a class, adhering to encapsulation and maintainability.