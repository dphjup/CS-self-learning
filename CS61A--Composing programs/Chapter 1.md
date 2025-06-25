## 1.1 Getting started



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
2. Only apply the function when 