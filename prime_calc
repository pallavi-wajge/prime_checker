# For numbers less than 100, square root will be less than 10, primes below 10 are 2, 3, 5, 7. If number to be checked is divisible by any of these, then it's not a prime number. Else it is prime. 

def prime_checker(number): 

  import math 

  # method Angela 

  # for i in (2,number): 

  #   if number % i == 0: 

  #     is_prime = False 

  #   else: 

  #     is_prime = True 


  root = math.sqrt(number) 

  #print(root) 

  if root <= 10: 

    if number == 1: 

      print(" 1 is neither prime nor composite.") 

    if number == 2 or number == 3 or number == 5 or number == 7: 

      print("It's a prime number.") 

    elif (number % 2 == 0) or (number % 3 == 0) or (number % 5 == 0) or (number % 7 == 0): 

      print("It's not a prime number.") 

    else: 

      print("It's a prime number.") 

  else: 

    print("Enter numbers less than 100 please.") 

  

while True: 

  n = int(input(" Enter a number less than 100 to check if it's prime. \n ")) # Check this number 

  

  prime_checker(number=n) 

   

 
