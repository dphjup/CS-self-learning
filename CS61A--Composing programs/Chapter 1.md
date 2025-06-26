## 1.1 Getting started
**Statements and expressions:**  instructions to 
1. compute some value ---- expression
2. carry out some action ---- statement

**Functions:** encapsulate logic that manipulates data (like some built blocks from elementary elements to perform some certain actions)

**Objects:** 

**Interpreters:** 



## 1.2 Elements of Programming

'Every powerful language has three mechanisms to combine simple ideas into complex ones':
- Primitive expressions of 'building blocks'
- Ways to combine such 'building blocks'
- Ways to use the 'bigger' or 'not so primitive' blocksimport
#### import

The idea of ** import ** is an important one (especially for a not-so-fast language like Python!).

#### environment
The significance of environment lies in that it indicates clearly the functions or variables to be called. Or, the environment seems to be the memory of 'blocks' that can be used in the scenario.

#### Assignment statements

- binding names to values
- binding names to functions
	```python
	>>> max
	<built-in function max>
	>>>f = max ##binding f to max
	>>>f(1,2) ##f acts just as max does
	2
	```
- values on the right are first evaluated and then bounded to the names on the left

#### The process of evaluation
1. Evaluate the operator and operand subexpressions.
2. Apply the function to values at the end points of the expression tree.

***The  expression tree and the application***
Indicates the natural idea of recursion.

#### Pure and non-pure pring functions
##### Pure functions
Given input, functions return some output. (*'The value of the function' is meaningful.*)

**Critical feature**: no other effect than returning a value(aka doing a 'calculation').

**Advantage:** 
	1. always return useful (or meaningful) results
	2. simpler to test
##### Non-pure functions
**Critical feature**: having some other effect than returning a value (like making some change to the state of the interpreter or computer)

**Example**: The print function
```python
>>> print(1,2,3)
1 2 3 #comma separates items rather than acts as something to be appeared in the output
>>> print(print(1,2,3))
1 2 3
None
>>> print(print(1),print(2))
1 #it seems that print()=printf("\n")in C
2
None None
```

*Remark:* That print outputs None indicates that it should be avoided when doing assignments.

While non-pure functions empowers strong features, we should be especially cautious when using them along with assignments.

## 1.3 Defining new functions
