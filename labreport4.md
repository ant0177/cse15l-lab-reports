# Lab Report #4: 

## Snippet #1:
What should be produced: 

[screenshot]

Snippet 1 passed on my implementation there was no Junit error. I believe that my implementation just ignored the backticks and looked for the brackets that were surrounding the link which allowed for the case to pass. I think you can also create a way to ignore the backticks inside the program by using an if statement

Code for snippet 1 in MarkdownParseTest.java:

[screenshot]

Week 7 Implementation:

The implementation I reviewed failed the test with Snippet #1

[screenshot]

---
## Snippet #2:
What should be produced:

[screenshot]

Snippet 2 failed my implementation: 

[screenshot]

I believe to fix my implementation, I need to find the very outer edges of the brackets and ignore all the ones inside. I think I would need to somehow detect the two very outer brackets to be the same and once that is correct, I can just keep everything inside that is not a bracket.

Code for snippet2 in MarkdownParseTest.java

[screenshot]

Week 7 Implementation: 

Snippet 2 passed the repository I reviewed, no Junit error was shown

---
## Snippet #3:

What should be produced:

[screnshot]

Snippet 3 failed my implementation:

[screenshot]

I think I would need to somehow check for empty lines in between the brackets. If there is an empty line I would have to ignore it and then find the close bracket in the next lines. I would also have to find a solution to not having a closed bracket. 

Code for snippet 3 in MarkdownParseTest.java

Week 7 Implementation:

Their implementation also failed snippet 3

[screenshot]







