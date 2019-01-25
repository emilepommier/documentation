# Streamroot DNA

For full documentation visit [mkdocs.org](https://mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.

## Step 1: Add Streamroot plugin




``` bash tab="Bash"
#!/bin/bash

echo "Hello world!"

```

``` c tab="C"
    #include <stdio.h>
    int main(void) {
    printf("Hello world!\n");
    }
```

``` c++ tab="C++"
#include <iostream>

int main() {
  std::cout << "Hello world!" << std::endl;
  return 0;
}
```

``` c# tab="C#"
using System;

class Program {
  static void Main(string[] args) {
    Console.WriteLine("Hello world!");
  }
}
```

#!/usr/bin/python
import tensorflow as tf