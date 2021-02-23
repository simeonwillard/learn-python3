# learn-python3
learning how to work with python3

## installing python3

Have homebrew installed on your machine.
Run 'brew install python3' if you dont have the current version.

## using python in vs-code

Have vs-code installed on your machine.
install python extension in vs-code.
select python interpreter by using cmd + p and typing >Python: select interpreter.
all python files should end in .py so that vs-code knows its python.

## quick programming examples with Python

- Variables and types:
    - defining a variable is as simple as msg = 'hello world' or num = 1
    - or define a variable with a specific data type: num = int(1)
    -  a string(str) data type, defined by single or double quotes
    - integers(int) (whole numbers), float numbers (decimals), and complex numbers (1j)
    -  boolean(bool)
    
- Data structures and loops:
    - arrays
    - lists, tuples, sets, dictionaries
    - lists are ordered, changeable, and allow duplicate values, they are indexed, x = ["train", "car", "bus"]
    - tuples are ordered, unchangeable, and allow duplicate values, they are indexed, x = ("train", "car", "bus")
    - sets are unordered, unchangeable, unidexed and do not allow duplicate values, x = {"train", "car", "bus"}
    - dictionaries, or dicts, are ordered, changeable, they are written in key:value pairs, and do not allow duplicate values
        x = {land: "train", sea: "boat", air: "plane"}
        
    - loops
    - while loop: 
          i = 1
          while i < 6:
            print(i)
            if i == 3:
              break
            i += 1
            
       OUTPUT: 1, 2, 3
            
            
    - for loops: 
        cars = ["truck", "sedan", "van"]
        for car in cars:
          print(car)
          
      OUTPUT: truck, sedan, van
      
      
 - Functions:
      - all functions are defined by using the keyword 'def' followed by parens 
     def fizz_buzz(number):
    if (number % 3 == 0 and number % 5 == 0):
        print('FizzBuzz')
    elif (number % 3 == 0):
        print('Fizz')
    elif (number % 5 == 0):
        print('Buzz')
    else:
        print(number)

    fizz_buzz(15) OUTPUT FizzBuzz
    fizz_buzz(3) OUTPUT Fizz
    fizz_buzz(5) OUTPUT Buzz
    fizz_buzz(1) OUTPUT 1
    
    
    def leap_year(year):
    if (year % 100 == 0 and year % 400):
        print(year, 'is a leap year')
    elif (year % 4 == 0):
        print(year, 'is a leap year')
    else:
        print(year, 'is not a leap year')

    leap_year(4) OUTPUT 4 is a leap year
    leap_year(2020) OUTPUT 2020 is a leap year
    leap_year(2018) OUTPUT 2018 is not a leap year
         
        
        
    


    
