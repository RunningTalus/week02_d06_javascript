README.md 

Introduction to JavaScript Lecture

1) Keep console open! Look for line #.
2) Use console.log
3) Indent properly
	-After opening curly brace({), indent one level.
	-Closing curly brace (}) on its own line at same indentation level as the opening curly brace ({).
4) Use the console to test JS Expressions
5) You can always substitute a value (or expression) of the same type and the code will still be functional

Notes from second morning lecture

	STRINGS

		typeof in Chrome Developer Tools Console
		typeof "RefactorU"
		returns string

		If in quotes, it is a "string literal"

		var first = "Stephen";
		var last = "Colbert";
		alert ("Hello " + first + " " + last + "!");

		ALL strings have a .length property

		Access characters in a string with []

		var name ="Stephen"
		name.length
		returns "Stephen"
		
		name[0]
		returns "S"
		
		name[11]
		returns undefined

	
	NUMBER

		var x =10;
		var squared = x *x;

		Number Operators
		Add +
		Subtract -
		Multiply *
		Divide /

		CANNOT USE DASHES IN VARIABLE NAMES
		MUST have QTY#2 OPERANDS
		
		Boolean Operator: Operand1 + Operand2
			the + sign above is an "infix" operator
		
		Unary Operator: ++ or --
			++ Operand1
			-Operand1
		
		Remainder Modulus Operator
			10 % 3 === 1

		Bit Shift Operator
			<<
			>>

		var celsius = (fahrenheit - 32) * 5/9;
		alert (celsius);

		JavaScript does NOT differentiate between integers and floats.  
			It will generally treat them as floats and does NOT perform rounding
				MUST use other Math Methods

	BOOLEAN

		var formIsValid = false;
		var isSunny = true;
		var isCloudy = !isSunny;
		alert(isCloudy);

		NOTE: === behavior expects to return either True or False.  
			=== is a comparison operator.  
		
		OPERATORS THAT EVALUATE TO BOOLEAN VALUES

		Equal To ===  
		Not Equal To !==
		And &&
		Greater Than >
		Greater Than or Equal To >=
		Less Than <
		Less Than or Equal To <=
		Or ||
		Not !

		true && false
		returns false

		"Chris" && "Raine"
		returns "Raine"

		"Raine" && "Chris"
		returns "Chris"

		WHY??? 
			Returns the last Operand/Value.

		//

		if (input.length === 0) {
				alert("Please enter a value.");
		}

		var isEmpty = input.length ===0;
		if (isEmpty) {
			alert("Please enter a value.");
		}
		
		ORDER OF OPERATIONS
		
		+, - , *, /
			===, !==,
			&&, ||


			=
		



		*****Review notes and update here*****
		TRUTH TABLES
		REVIEW

typeof undefined
returns "undefined"