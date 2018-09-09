
# First comment on README

#Question.1:

#let  fizzBuzz = fs.readFileSync('./src/js/fizz-buzz.js'); 
#eval( fizzBuzz + `\nexports.FizzBuzz = FizzBuzz;`)

# Creatating a block variable (let) named fizzBuss (A let variable can be modified) 
# The = , is setting the variable eq to a method (fs.readFileSync) which purpose is to return the content of the file named ('./src/js/fizz-buzz.js').

# The eval() is a function that evaluates or executes an argument. In this example the argument is (fizzBuzz + `\nexports.FizzBuzz = FizzBuzz;`), 
# The \n means new line.
# I think here the eval function is an expression and not an statement. Expression = evaluation, statement = execution.

# Which means that when we call fizzBuzz in our code we get the content of the file ('./src/js/fizz-buzz.js') evaluated and exported.
#Sourses I have used for learning more about Question.1 is stackoverflow.com and w3schools.com.

#Question.2:

# We are declaring the "let fizzBuzz = new FizzBuzz" outside the "it block" because we want to use it for more than one test.

#Question.3:

#The difference between using === and == in JS is, == can compare different data types, and === can only compare the same type of data.

#Question.4:

#We move (number % 5 === 0) to the top because the method wont TO DO 

