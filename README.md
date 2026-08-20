# Hello World

A simple C program demonstrating standard output execution.

## Documentation & Google-Style Docstring Examples

When writing Python wrappers or helper scripts for this project, follow the Google-style docstring standard shown below:

```python
def print_hello(name: str = "World") -> str:
    """Generates a hello greeting message.

    Args:
        name (str): The name to greet. Defaults to 'World'.

    Returns:
        str: A formatted greeting string.

    Examples:
        >>> print_hello()
        'Hello, World!'
        >>> print_hello("Alice")
        'Hello, Alice!'
    """
    return f"Hello, {name}!"
```

## Building and Running

To compile and run `hello.c`:

```bash
gcc hello.c -o hello
./hello
```
