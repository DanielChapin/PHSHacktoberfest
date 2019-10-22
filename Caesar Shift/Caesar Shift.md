# Caesar Shift
Create a function that is passed a string, `message`, with all lower cased letters and spaces and a `shiftIndex` that returns the Caesar Shifted version of the message.

The Caesar Shift is when you give each letter of the alphabet an index and you change the index of each letter without changing the indexes of the characters in the message.

Examples:
```
shiftIndex = 1
a (0) -> b (1)
c (2) -> d (3)

shiftIndex = 2
a (0) -> c (2)

shiftIndex = 1
abc -> bcd

shiftIndex = 2
abc -> cde
```

Ignore spaces.
