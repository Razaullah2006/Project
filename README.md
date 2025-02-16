# Programming Languages and Data Structures

## Table of Contents
- [Java](#java)
- [C](#c)
- [C++](#c-1)
- [HTML](#html)
- [Data Structures](#data-structures)

## Java
Java is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible.

### Features
- Platform-independent (Write Once, Run Anywhere)
- Object-oriented
- Robust and secure
- Multi-threaded
- High performance with JIT compilation

### Example Code
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

## C
C is a general-purpose, procedural programming language that provides low-level access to memory and is widely used for system programming.

### Features
- Low-level programming capabilities
- Fast execution
- Structured programming
- Rich set of built-in operators

### Example Code
```c
#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}
```

## C++
C++ is an extension of C that includes object-oriented programming features.

### Features
- Supports both procedural and object-oriented programming
- Strongly typed
- Rich standard library (STL)

### Example Code
```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "Hello, World!" << endl;
    return 0;
}
```

## HTML
HTML (HyperText Markup Language) is the standard language for creating web pages.

### Features
- Markup language for structuring web content
- Supports multimedia elements
- Works with CSS and JavaScript

### Example Code
```html
<!DOCTYPE html>
<html>
<head>
    <title>My Web Page</title>
</head>
<body>
    <h1>Hello, World!</h1>
</body>
</html>
```

## Data Structures
Data structures are fundamental concepts used to organize and store data efficiently.

### Common Data Structures
- **Arrays**: Collection of elements stored at contiguous memory locations.
- **Linked List**: A sequential collection of elements, where each element points to the next.
- **Stack**: A Last In, First Out (LIFO) structure.
- **Queue**: A First In, First Out (FIFO) structure.
- **Binary Tree**: A hierarchical structure where each node has at most two children.
- **Hash Table**: A structure that maps keys to values using a hash function.

### Example Code (Stack in C++)
```cpp
#include <iostream>
#include <stack>
using namespace std;

int main() {
    stack<int> s;
    s.push(1);
    s.push(2);
    s.push(3);
    
    while (!s.empty()) {
        cout << s.top() << " ";
        s.pop();
    }
    return 0;
}
```

---
### Contributing
Feel free to fork this repository and contribute to it by adding more content or improving the examples.

### License
This project is licensed under the MIT License.
