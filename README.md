# Hello World

A simple C program demonstrating clean execution and Google-style code documentation.

## Build and Run

Compile and execute the C program using `gcc`:

```bash
gcc -o hello hello.c
./hello
```

## Code Examples with Google-Style Docstrings

### Python Example

```python
def greet(name: str = "World") -> str:
    """Generates a greeting message.

    Args:
        name (str): The name of the entity to greet. Defaults to "World".

    Returns:
        str: A formatted greeting string.

    Examples:
        >>> greet("Alice")
        'Hello, Alice!'
        >>> greet()
        'Hello, World!'
    """
    return f"Hello, {name}!"
```

### C Example

```c
/**
 * Main entry point of the application.
 *
 * Prints a greeting message to standard output.
 *
 * Returns:
 *     0 upon successful execution.
 */
int main(void) {
    printf("Hello, World!\n");
    return 0;
}
```
