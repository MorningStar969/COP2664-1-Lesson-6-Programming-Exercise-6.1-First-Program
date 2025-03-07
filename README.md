# COP2664-1-Lesson-6-Programming-Exercise-6.1-First-Program
This is a GitHub repository link for the first program of Programming Exercise 6.1 from Lesson 6.

// This program to calculate a function within a function by doing multiple calculations with different variables and operations.

func performCalculation(a: Int, b: Int, operation: (Int, Int) -> Int) -> Int { // This function is used to perform a calculation on two numbers.
  return operation(a, b) // This returns the result of the calculation.
}
let result = performCalculation(a: 69, b: 96, operation: { (a, b) in // This is the function that performs the calculation.
  return a * b // This is the calculation that is performed.
})
print(result) // This prints the result of the calculation.
let result2 = performCalculation(a: 69, b: 96, operation: { (a, b) in
  return a + b // This is the calculation that is performed.
})
print(result2) // This prints the result of the calculation.
let result3 = performCalculation(a: 69, b: 96, operation: { (a, b) in // This is the function that performs the calculation.
  return a - b // This is the calculation that is performed.
})
print(result3) // This prints the result of the calculation.
let result4 = performCalculation(a: 69, b: 96, operation: { (a, b) in
  return a / b // This is the calculation that is performed.
})
print(result4) // This prints the result of the calculation.
