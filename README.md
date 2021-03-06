# Simple Programming Language

## Syntax

#### PRIMITIVE TYPES
```
i = 3       INTEGER
f = 3.5     FLOAT
s = 'text'  STRING 
b = True    BOOLEAN 
```

#### PRINT COMMAND
```
print 'text\n'
println 2 + 2 - 6 * 9 / 2
```

#### COMMENTS
```
# comment   SINGLE-LINE COMMENT
```

#### VARIABLES
```
var a = 3           VARIABLE
let b = 5.4         CONSTANT
println a + a - b
```

#### BOOLEAN OPERATIONS
```
println a < b 
println a <= b
println a > b
println a >= b
println a == b
println a not b
println a not b and a < b
println a not b or a < b
```

#### IF-ELSE OPERATOR
```
if a > b {
    println 'a > b'
} else if a < b {
    println 'a < b'
} else {
    println 'a = b'
}
``` 
OR
```
if a > b:
    println True
else:
    println False
```

#### TERNARY OPERATOR
```
min = a if a < b else b
```

#### WHILE OPERATOR
```
i = 0
while i < 10 {
    println i
    i = i + 1
}
```

#### DO-WHILE OPERATOR
```
do {
    println i
    i = i + 1
} while i < 10
```

#### FOR OPERATOR
```
for i = 0; i < 10; i = i + 1 {
    println i
}
```

#### COMPOSITE TYPES
```
arr = [
  123, 
  '3432', 
  True, 
  ['first', 'second', 'third']]     ARRAY
  
dict = {
  'First': 1, 
  'Second': '2', 
  'Third': True }                   DICTIONARY
```

#### FUNCTION
```
func min(n1, n2) {
    return n1 if n1 < 2 else n2
}
```
