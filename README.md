# homework1
def greet(*args):
    for name in args:
        print(f"Hello, {name}!")

greet("Alice","Bob","Frank")


def greet(*args):
    for age in args:
        print(f"I am {age} years old")
greet(17)



def sum_numbers(*args):
    total = sum(args)
    return total
result = sum_numbers(2,6,4,3)
print(result)


def multiply_numbers(*args):
    result = 1
    for num in args:
      result *= num
    return result
    
print(multiply_numbers(4,7,5))


def longest_number(*args):
    longest = (max(args))
    return longest
result = longest_number(2,6,4,3)
print(result)



def is_even(args):
    return args % 2 ==0

numbers = [1,2,4,7,8,10,6]

result = filter(is_even, numbers)
print(list(result))
