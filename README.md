# fibonacci-series-in-python
fibonacci series in python
def fibonacci(n):
    a = 0
    b=1
    while a <= n:
        print(a, end=' ')
        a, b = b, a + b

fibonacci(50)

