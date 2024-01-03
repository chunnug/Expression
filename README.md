## Expression
Using an Arraydeque as a stack, various arithmetic equations, from infix or postfix, are either parsed or evaluated. In this code, a token can represent various operators such as plus, times, minus, etc. The token can also represent operands, which are of token type 'number.'

## How it's made
**Tech used:** Java, NetBeans IDE
The methods I have coded are the following
'getToken': parse a string to a token.
'infixToExpression': parse infix expression into an expression tree. The expression tree is formed via an inner class Expression which was not created by me but was used by me to be populated by tokens. 
'infixToPostfix':  parse a given infix expression to postfix.
'evaluatePostfix': method to evaluate the result of a postfix expression.
'evaluateExpression': method to evaluate the result of an expression tree.

## Optimizations

## Lessons learned

