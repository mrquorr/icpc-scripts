# What is it?
script for automatically running a c++ program and testing it in console

# How to use it?
write your program with the following structure

```cpp
/*
test cases
*/

#include <stdio.h>
#include <algorithm>
#include <vector>
#include <cmath>
#include <iostream>

using namespace std;
struct mystruct{
  int size;
};

int main(){
 printf("true");
}
```

and now just run `./script myprogram.cpp`

It just works!
