# Super Crazy Bonus Release

Edit this file to answer the following questions. Give examples. You may need to do a bit of research. :)

1. Why is Hash.fetch useful?
#fetch allows you to access the value if the key exists or return nil or a default value if the key doesn't exist. It's very useful when using an args = {} initialization.

2. What is the disadvantage of single inheritance, and what's a possible solution to that problem?
the disadvantage of single inheritance is that it limits the attributes or methods that can be inherited. multiple inheritance allows classes to inherit different attributes/methods from multiple parents.

3. Why are these classes initialized with an options hash?
to make it easier to access the attribute values during an instance initialization.

4. What is the purpose of the private keyword in a class? What does it protect you from and why is that valuable?
the private keyword protects any code it encapsulates from being accessed by other classes. It protects things that shouldn't be changed, i.e. @age in the orange_tree challenges.

5. Why are concepts like encapsulation, single responsibility, and abstraction important? Now that you've been programming for a while, have you seen any advantages for yourself, or can you imagine them in the future?
they help make code more efficient, by reducing the amount of code repetition and redundancy. increasing DRYness.
single responsibility makes debugging easier and code more concise.
