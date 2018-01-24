Brandon Zink 
Partner: Cameron Connor
PPL
Lab 1 Writeup

2a.

The use of pi at line 4 is bound on line 3, since pi is redeclared using val within the brackets, and will be mapped to 3.14159 until the closing bracket on line 5.

The use of pi at line 7 is bound on line 1 since pi is not redelcared within the scope of the area function, so it uses the original decleration.

2b.

The use of x at line 3 is bound by the function parameter on line 2.

The use of x at line 6 is bound by the function parameter on line 2, but line 6 will only excectue if x does not equal 0.

The use of x at line 10 is bound by the function parameter on line 2 since the x on line 8 is a part of a different scope. 

The use of x at line 13 is bound on line 1 since line 13 is outside of the f functions scope.

3.

If a valid return type is included in the code, it would be considered well typed wince the code is consistent (becuase there is both an if and an else statement that covers all posibilities). 

(a,b): (int, (int, int))
	a: int becuase
		1: int
	b: (int, int) because
		x: int
		3: int