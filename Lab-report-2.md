# Lab Report #2 Test-Driven & Incremental Development

## Code Change #1:

![Modified](https://user-images.githubusercontent.com/103216296/165033645-037ce5e6-044d-4beb-a8be-ed0dbc85b69b.png)


[TestFile1](https://github.com/ant0177/markdown-parser/commit/35e7e8bbea57bc4bd733a9be7b7aa2be17c270c6)

![Symptom1](https://user-images.githubusercontent.com/103216296/165033726-6ad7f3a4-290b-4840-9b7e-fda6be616d8c.png)

The first code change involved an empty extra line in the test file. The symptom of the bug is a java out of memory error in line 37 when reading the file content. The bug was caused by the extra line in test file which the code was unable to read thus causing the error.

## Code Change #2:
![Modified2](https://user-images.githubusercontent.com/103216296/165033834-a71ee3e9-7c43-4c99-8888-5b9f77119066.png)


[TestFile2](https://github.com/ant0177/markdown-parser/commit/b57f7a0d382c5ca493fc30663ce4abb4a6f60ad7#diff-d902b3a6dba925548b7ea18ffb80dd0c28f1bc45f1d738a5da414273711a4409)

![Symptom2](https://user-images.githubusercontent.com/103216296/165033894-0d6fff08-5fb0-4089-a517-496e1237da33.png)


For the second change, we added more brackets to the link. The symptom it caused was an infinite loop. The bug was due to the code never exiting the while loop which caused it to run forever.

## Code Change #3:

![Modified3](https://user-images.githubusercontent.com/103216296/165034100-fd024829-b086-4abd-b21d-4a9f6de378e9.png)


[TestFile3](https://github.com/Tyler-Culp/markdown-parser/commit/37d107b473f219538441aaa25b511ff060b5ff77)

The bug in test 3 was caused when a weird link was used inside the text which caused the code to not work properly and cause an exception error. 
