# Lab Report #4: 

## Snippet #1:
What should be produced: 

![actual #1](https://user-images.githubusercontent.com/103216296/171098420-a341caf2-07e8-41f2-a15e-4c3b947c3773.png)

Snippet 1 passed on my implementation there was no Junit error. I believe that my implementation just ignored the backticks and looked for the brackets that were surrounding the link which allowed for the case to pass. I think you can also create a way to ignore the backticks inside the program by using an if statement

Code for snippet 1 in MarkdownParseTest.java:

![codesnippet1](https://user-images.githubusercontent.com/103216296/171098535-650dc650-907d-4bdb-acdf-ae20e8689ae8.png)

Week 7 Implementation:

The implementation I reviewed failed the test with Snippet #1

![codesnippet1](https://user-images.githubusercontent.com/103216296/171098591-88682407-2f1a-4ba1-a8c8-8af5bb954948.png)

---
## Snippet #2:
What should be produced:

![codesnippet1](https://user-images.githubusercontent.com/103216296/171098631-419f1070-73d0-4fdc-a57b-701a0e5bfac5.png)

Snippet 2 failed my implementation: 

![snippet2fail](https://user-images.githubusercontent.com/103216296/171098807-df51d8c8-d226-4ba6-8648-9e7812a92aaa.png)

I believe to fix my implementation, I need to find the very outer edges of the brackets and ignore all the ones inside. I think I would need to somehow detect the two very outer brackets to be the same and once that is correct, I can just keep everything inside that is not a bracket.

Code for snippet2 in MarkdownParseTest.java

![codesnippet2](https://user-images.githubusercontent.com/103216296/171098866-4c6e0541-5906-46dc-9f96-bfef576b0bfa.png)

Week 7 Implementation: 

Snippet 2 passed the repository I reviewed, no Junit error was shown

---
## Snippet #3:

What should be produced:

![actual #3](https://user-images.githubusercontent.com/103216296/171098908-a824c134-088f-4b90-91b0-242b75bb8d9d.png)

Snippet 3 failed my implementation:

![snippet3fail](https://user-images.githubusercontent.com/103216296/171098983-7e0f497a-0798-4d5f-807a-d54fe302d4f8.png)

I think I would need to somehow check for empty lines in between the brackets. If there is an empty line I would have to ignore it and then find the close bracket in the next lines. I would also have to find a solution to not having a closed bracket. 

Code for snippet 3 in MarkdownParseTest.java

![codesnippet3](https://user-images.githubusercontent.com/103216296/171099052-353f1e57-5459-4d7a-8a5d-e80d181d7b1d.png)

Week 7 Implementation:

Their implementation also failed snippet 3

![week7snippet3](https://user-images.githubusercontent.com/103216296/171099130-c29caf60-3e83-46f9-8821-a642ffe83b1a.png)

**Link to both repositories:**

[my repository](https://github.com/ant0177/markdown-parser)

[week 7 repository](https://github.com/nquach1515/markdown-parser-cse15l)






