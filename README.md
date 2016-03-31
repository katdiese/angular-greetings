*What are Angular expressions? How do they compare to tags from templating engines you've used before?
  > Expressions can be tied to ng-models to synch information automatically. They are similar in that they are like variables to be changed in your code.

*What happens when you write invalid code in an expression? What type of error do you get?
>it breaks the rest of the expressions with a parse syntax error

*What are Angular filters? Describe what a filter does and then name four built-in filters, including one that we haven't used yet.
>filters format the expression in your view

*What's the syntax for filters?
> they appear after a pipe {{ expression | filter }}

*Can you use more than one filter?
>yes

*We'll soon see how to create custom filters. What is a use case for a custom filter?
>the code you want to display is formatted in a way that is not described in the auto filters included in Angular