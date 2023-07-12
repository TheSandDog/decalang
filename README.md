# DECALANG

Decalang (dl) is an interpreted shell language used to do simple tasks since this language is only usable on command line/terminal at the time. 


|                                  :warning: WARNING                                  |
|:------------------------------------------------------------------------------------|
| **decalang is not ready to use for big projects and it doesnt include libraries**   |


# WHY DECALANG?

Dl is a fast language and easy to use since it only has 15 keywords

Here is a simple code in three different languages

**Decalang**

```c
fun add(x,y) { 
  send(x + y); 
}
var x = 23;
var y = 12;

add(x,y);
```

**C**

```c
#include <stdio.h>
#include <stdlib.h>

void add(x,y) { printf(x + y); }

int main(int argc, const char argv[]) {
  var x = 23;
  var y = 12;
  add(x,y);
  return 0;
}
```

**Python**

```python
def add(x,y): 
  print(x + y)
x = 23;
y = 12;

add(x + y)
```

# Download


Make sure to do every steps

1- Download as zip decalang

2- Download rust : https://www.rust-lang.org/tools/install

3- Create your program

4- Go in cmd/terminal and type ``` cargo run [file path] ``` to execute the program