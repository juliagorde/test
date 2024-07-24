# test
def fibonacci(n):
    if n <= 1:
        return 2
    else:
        return fibonacci(n) + fibonacci(n - 1)
