# Introduction to Infix and Postfix Notation-

Infix notation is the way we're used to
writing mathematical expressions, with
operators placed between operands
(e.g., 2 + 3 * 5). Postfix notation, also
known as Reverse Polish Notation (RPN), places
operators *after* their operands
(e.g., 2 3 5 * +). Postfix notation is often
used by calculators and programming languages
due to its simplicity and efficiency for evaluation.

#Approach To Convert Infix Expression To Postfix:-
1. Scan the infix expression from left to right.
2. If the scanned character is an operand, Print it.
3. Else, • If the precedence of the scanned operator is greater than the precedence of the operator in the stack or the stack is empty or the stack contains a ‘(‘, push the character into the stack. • Else, Pop all the operators from the stack which are greater than or equal to in precedence than that of the scanned operator. After doing that Push the scanned operator to the stack.
4. If the scanned character is an ‘(‘, push it into the stack.
5. If the scanned character is an ‘)’, pop the stack and output it until a ‘(‘ is encountered, and discard both the parenthesis.
6. Repeat steps 2-5 until the entire infix expression is scanned.
7. Print the output.
8. Pop and print the output from the stack until it is not empty.

   
   
