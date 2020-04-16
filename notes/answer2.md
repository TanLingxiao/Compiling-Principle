- 3.1
 
a. 
```
S -> E
S ->
E -> x Y x
Y -> yY
Y ->
E -> y X y
X -> xX
X ->
```

b. 
```
S -> E
E -> A.B
E -> B.A
A -> C B
B -> C B
B ->
C -> 0
C -> 1
```

- 3.3

a.
```
S -> E
E -> aEa
E -> bEb
E -> a
E -> b
E ->
```

b.
```
S -> E
E -> aEF
F -> b
F ->
```

c.
```
S -> E
E -> (E)E
E -> [E]E
E ->
```

d.
```
S -> E
E -> (E)E
E -> (F)E
E ->
F -> (E)
F -> [F]
F -> (E
F ->
```

f.
```
S -> (X)
X -> E; X
E -> (X)
X -> E
E -> statement
```

g.
```
S -> {X}
X -> EX
X ->
E -> {X}
E -> expression
```

- 3.4
```
S -> XY
Y -> ; S
Y ->
X -> id := E
X -> print(L)
E -> id
E -> num
E -> T + E
T -> EM
M -> +E
M ->
E -> (S, E)
L -> EN
N -> ,L
N ->
```

- 3.5

|     |Nullable| First | Follow |
| ---- | ----  | ----  |  ----  |
| S'| N | \,{, WORD, begin, end$ | |
| S | Y | \,{, WORD, begin, end | $,},\ |
| B | N | \ | \,{, WORD, begin, end$} |
| E | N | \ | \,{, WORD, begin, end |
| X | N | \,{, WORD, begin, end | \,{, WORD, begin, end |