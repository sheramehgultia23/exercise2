Define the numbers
a_int = 10
b_int = 4

a_float = 10.0
b_float = 4.0

a_complex = 10 + 4j
b_complex = 4 + 2j

# Arithmetic operations for integers
print("Integer Operations:")
print(f"Addition: {a_int} + {b_int} = {a_int + b_int}")
print(f"Subtraction: {a_int} - {b_int} = {a_int - b_int}")
print(f"Multiplication: {a_int} * {b_int} = {a_int * b_int}")
print(f"Division: {a_int} / {b_int} = {a_int / b_int}")
print(f"Modulus: {a_int} % {b_int} = {a_int % b_int}")
print(f"Exponent: {a_int} ** {b_int} = {a_int ** b_int}")

# Arithmetic operations for floats
print("\nFloat Operations:")
print(f"Addition: {a_float} + {b_float} = {a_float + b_float}")
print(f"Subtraction: {a_float} - {b_float} = {a_float - b_float}")
print(f"Multiplication: {a_float} * {b_float} = {a_float * b_float}")
print(f"Division: {a_float} / {b_float} = {a_float / b_float}")
print(f"Modulus: {a_float} % {b_float} = {a_float % b_float}")
print(f"Exponent: {a_float} ** {b_float} = {a_float ** b_float}")

# Arithmetic operations for complex numbers
print("\nComplex Operations:")
print(f"Addition: {a_complex} + {b_complex} = {a_complex + b_complex}")
print(f"Subtraction: {a_complex} - {b_complex} = {a_complex - b_complex}")
print(f"Multiplication: {a_complex} * {b_complex} = {a_complex * b_complex}")
print(f"Division: {a_complex} / {b_complex} = {a_complex / b_complex}")

# Note: Modulus and Exponent operations are not defined for complex numbers
print(f"Modulus: Not defined for complex numbers")
print(f"Exponent: {a_complex} ** {b_complex} = {a_complex ** b_complex}")
