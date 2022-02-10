# ZLang
The Z Programming language

## Syntax
```
// Comments

/*
* Multi
* Line
* Comment
*/


// Variables
x: u8 = 10
x+=1

y: str = "";
y+="a"

l: [u32] = [1, 2, 3, 4, 5]
l2: [u32] = [5]*500;
l3: [u32] = [5 for i in ..500 if i % 2 == 0]
l = l2 + l3

// Conditionals
if x == 10 {
  y+="1"
} elif x == 7 {
  y+="1"
}

for i in l {
  print(f"{i} is the {x} index \{\}")
}

// Functions
fn func1(x: int, y: int) -> int {
}





```
