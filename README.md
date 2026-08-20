# Hello World Project

This repository provides simple implementations formatted according to Google-style docstring and commenting conventions.

## Overview & Conventions

Code standard formatting follows Google style guidelines for docstrings and header comments.

### C Example (`hello.c`)

```c}
#include <stdio.h>

// Main entry point of the application.
//
// Prints a standard greeting message to standard output.
//
// Returns:
//   0 on successful execution.
int main(void) {
    printf("Hello, World!\n");
    return 0;
}
```

### Python Example (Google Docstring Format)

```python
def hello_world(name: str = "World") -> str:
    """Generates a friendly greeting string.

    Args:
        name (str): Name of the person or entity to greet. Defaults to "World".

    Returns:
        str: Formatted greeting message.

    Examples:
        >>> hello_world("Alice")
        'Hello, Alice!'
    """
    return f"Hello, {name}!"
```

## Compilation and Running

To compile and execute `hello.c`:

```bash
gcc hello.c -o hello
./hello
```
