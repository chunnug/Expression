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


## tests
### Test infix expressions
The result should properly write infix as is and convert to postfix, keeping in mind PEMDAS order
```
253 + 746
999 + 0
( 13 * 12 ) - ( 48 / 3 ) + 66
3 + 4 * 5 - 10
( 21 * 370 / ( 482 + 50 - 32 * ( 2 + 4 ) / 71 ) ) ^ 2
2 ^ ( 3 + 2 ) ^ 2 - 1
( 1 + 2 * 3 - 4 % 5 + 6 * 7 - 8 / 9 * 10 + 11 - 12 * 13 + 14 / 15 - 16 + 17 * 18 - 19 * 20 ) 
```
### Test edge cases
if the equation cannot be parsed, it will either return the expression in the first case, or an error if the equation is not properly inputted in the second case

```
42
2 (
```
## Acknowledgment
* Base code and comments, not including the Javadoc for my methods, were done by Sridhar Alagar 



