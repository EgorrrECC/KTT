```pseudo
int fibonacci(int number) {
    int f1, f2 = 0, 1;

    for index in 1..number {
        f1, f2 = f2, f1 + f2;
    }

    return f1;
}
```
