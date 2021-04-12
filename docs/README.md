#### Exercise 9.11
The Device class must have a definition of getName(). However, the actual implementation can be in the Printer class.
#### Exercise 9.12
In that case the Printer class implementation of getName will be executed because it overrides the Driver class one.
#### Exercise 9.13
the string s will contain the student adress which is in hexadecimal numbers.
#### Exercise 9.14
Yes, the println() method of System.out internally calls the toString() method of the passed object.
#### Exercise 9.15
Yes, it will compile. It will print the names of the students, each name followed by a new line. All classes in Java extend the Object class implicitly so Object is a superclass of Student and Student overrides the toString() method of Object and as such the Student class' toString() method will be called in the println() call.
#### Exercise 9.16
```java
T x = new D();
```

#### Time complexity
addFirst O(1).

addLast O(1).

getFirst O(1).

getLast O(1).

get(int index) O(n).

removeFirst O(1).

clear O(1).

size O(1).

toString O(n).
