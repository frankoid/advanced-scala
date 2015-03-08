## Summary

While monads and functors are the most widely used types we've covered in this book, applicatives are the most general. Applicatives provide a generic mechanism to apply functions within a context, from which we can fashion monads, functors, and a variety of other combinators.

Applicatives are most commonly used as a means of combining independent values such as the results of validation rules. Scalaz provides the `Validation` type for this specific purpose, along with applicative builder syntax as a convenient way to express the combination of rules.

We have now covered all of the functional programming concepts on our agenda for this book. The remainding chapters dive into detail, using the concepts covered in a collection of case studies. We'll implement our own mapreduce system, solve data validation once and for all for all HTML forms, and even invent our own programming language.