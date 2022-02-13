# python-function
fungsi#2

#example

INPUT:

ef fibo(n):
    a = 0
    b = 1
    for i in range(0, n):
        temp = a
        a = b
        b = temp + b
    return a

# Show the first 13 Fibonacci numbers.
for c in range(0, 13):
    print(fibo(c)) #Function call
    
    OUTPUT:
    
    0
1
1
2
3
5
8
13
21
34
55
89
144
