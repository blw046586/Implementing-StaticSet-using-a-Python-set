# Implementing-StaticSet-using-a-Python-set
Step 1: Inspect StaticSet.py
Inspect the StaticSet class declaration in the StaticSet.py file. Access StaticSet.py by clicking on the orange arrow next to main.py at the top of the coding window. StaticSet uses a Python set to implement a static set. The set's contents are assigned at construction time and must not change after.

Constructors and some additional methods are already implemented:

contains(element) returns True if element is in the set and returns False otherwise.
get_size() uses the len() method of the Python set to determine the number of elements in the set. get_size() returns the set's size.
Step 2: Implement StaticSet's union(), intersection(), difference(), filter(), and map() methods
Implement the StaticSet class's union(), intersection(), difference(), filter(), and map() methods. Each must not change the StaticSet itself, but rather build and return a new StaticSet.

Step 3: Test in develop mode, then submit
File main.py contains test cases for each of the five operations. Running code in develop mode displays the test results, with 3 points possible for the union(), intersection(), and difference() operations, and 2 points for the filter() and map() operations. After each method is implemented and all tests pass in develop mode, submit the code. The unit tests run on submitted code are similar, but use different sets and element types.
