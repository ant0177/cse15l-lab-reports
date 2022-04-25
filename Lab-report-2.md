# Lab Report #2 Test-Driven & Incremental Development

## Code Change #1:
[screenshot] - code change diff

[TestFile1](https://github.com/ant0177/markdown-parser/commit/35e7e8bbea57bc4bd733a9be7b7aa2be17c270c6)

[Symptom Screen Shot]

The first code change involved an empty extra line in the test file. The symptom of the bug is a java out of memory error in line 37 when reading the file content. The bug was caused by the extra line in test file which the code was unable to read thus causing the error.

## Code Change #2:
[screen shot code diff]

[TestFile2](https://github.com/ant0177/markdown-parser/commit/b57f7a0d382c5ca493fc30663ce4abb4a6f60ad7#diff-d902b3a6dba925548b7ea18ffb80dd0c28f1bc45f1d738a5da414273711a4409)

[symptom screen shot]

For the second change, we added more brackets to the link. The symptom it caused was an infinite loop. The bug was due to the code never exiting the while loop which caused it to run forever.

## Code Change #3:

[code change screenshot]

[TestFile3](https://github.com/Tyler-Culp/markdown-parser/commit/37d107b473f219538441aaa25b511ff060b5ff77)

The bug in test 3 was caused when a weird link was used inside the text which caused the code to not work properly and cause an exception error. 
