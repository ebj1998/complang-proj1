# Programming Project 1: Lessons Learned by Brady Murphy and Evan Jones

We learned a lot through demands from the emperor as a royal information officer and various requests at a boutique investing firm. In our first role as the royal information officer we created a parser for roman numerals in swift. Then, in the second role at the boutique investing firm we created a top down grammar parser in Python. Through analyzing these two distinct roles and tasks associated with he roles, we will explore our overall experience and lessons learned.

## Swiftly Parsing Roman Numerals

![Image of Swift Roman](https://learnappmaking.com/wp-content/uploads/2019/05/roman-numerals-swift-770x400.jpg)

This task reminded us a lot of a programming problem a company might give for an interview, but it still created some interesting things learned due to it being in Swift. While going to create our parser, we learned about Swift as a language and what makes it unique. 

One area we found was that Swift dealt with if-else semantic errors in an interesting way. We noticed that brackets must wrap any if-else statement completely. Also, Swift did not need the use of parenthesis for the boolean statement, yet it allowed the use regardless.

Another area we found interesting was through Swifts flexibility and minor limitations. We found that Swift was both a scripting and statically typed language depending on the use case. The support for Unicode characters natively also struck us as we had never seen a programming language have such easy support for Unicode. One area of limitation, however, was how indexing of strings (due to strings being various length) was not as intuitive as other languages we have worked with.

## Investing in Grammar

![Image of Python](https://static.makeuseof.com/wp-content/uploads/2018/03/python-faq-670x335.jpg)

As both of us have used Python in the past, our learning here focused on learning about top down parsers grammar creation in general. 

We found that the one big lesson about top down parsing we learned was to not use left recursion. We didn't understand initially why many online forums were saying not to do it until we actually started to code our own. We saw almost instantly how it would break the flow of recursion and break the ability to look ahead as right recursion could.

We learned another  lesson through the general construction and execution of grammar rules. We noticed how a user could easily break grammar with methods like adding whitespace, removing whitespace, missing tokens, or other measures. It was interesting to see what aspects we could account for and recover from in a more complex grammar and what we would not be able to.

Finally, through both of these areas we learned how flexible grammars could be. Both within the design of a top down parser and in the general construction of a grammar, we learned that adding a new rule was fairly straightforward. In the last section we added the ability to cancel a trade, which we simply added another trade rule. This fit perfectly within the grammar and in the parser.

## Conclusion

Through these tasks we can better understand Swift, grammars, and parsing in general. All of these lessons will allow us to better carry out solutions like this in the future.
