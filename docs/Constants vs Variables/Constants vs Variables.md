### **Constants vs Variables**

A **variable’s value** can change during program execution.
If you want a value that **never changes**, use the `const` keyword.

Example:

```c
const float PI = 3.1416;
```

Trying to change `PI` will cause an error.

---

### **Example Program Using Variables**

```c
#include <stdio.h>

int main() {
    int age = 19;          // integer variable
    float height = 5.9;    // decimal number
    char grade = 'A';      // single character

    printf("Age: %d\n", age);
    printf("Height: %.1f\n", height);
    printf("Grade: %c\n", grade);

    return 0;
}
```

**Output:**

```
Age: 19
Height: 5.9
Grade: A
```

---
