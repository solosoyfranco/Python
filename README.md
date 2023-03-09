# Python
A collection of notes and challenges


### Fizz Buzz
```
for number in range(1, 101):
    if number % 15 == 0:
        print("FizzBuzz")
    elif number % 5 == 0:
        print("Buzz")
    elif number % 3 == 0:
        print("Fizz")
    else:
        print(number)
```

### Prime or composite
```

def prime_checker(number):
  result = "It's a prime number."
  square_sum = 1
  result_square = 1
  while not result_square > n:
    square_sum += 1
    result_square = square_sum * square_sum
    div = n / square_sum
    div2 = n % square_sum

    if div2 == 0:
      result = "It's not a prime number."
    
      
  print(result)


# user input
n = int(input("Check this number: "))
prime_checker(number=n)

```