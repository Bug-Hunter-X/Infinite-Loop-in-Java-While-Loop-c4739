# Infinite Loop Bug in Java
This repository demonstrates a common error in Java programming: an infinite loop caused by an improperly placed or missing `break` statement in a `while` loop.

## Bug Description
The Java code in `bug.java` contains a `while` loop intended to print numbers from 0 to 4. However, due to the placement of the `break` statement, if `x` becomes 5, the loop will terminate correctly. But this should print from 0 to 9, so there's potential for an infinite loop if this condition is not met.