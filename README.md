
# What is FizzBuzz#

##Deployed website##

##Built with JavaScript, using Unit and Feature test running npm##

##Answer##

#Question 1. In your README to the best of your knowledge please explain what the following lines of code do

<!-- let  fizzBuzz = fs.readFileSync('./src/js/fizz-buzz.js'); 
eval( fizzBuzz + `\nexports.FizzBuzz = FizzBuzz;`) -->

# Creatating a block variable (let) named fizzBuss (A let variable can be modified) 
# The = , is setting the variable eq to a method (fs.readFileSync) which purpose is to return the content of the file named ('./src/js/fizz-buzz.js').
# The eval() is a function that evaluates or executes an argument. In this example the argument is (fizzBuzz + `\nexports.FizzBuzz = FizzBuzz;`), 
# The \n means new line.
# I think here the eval function is an expression and not an statement. Expression = evaluation, statement = execution. ?
# Which means that when we call fizzBuzz in our code we get the content of the file ('./src/js/fizz-buzz.js') evaluated and exported.

#Question 2. In your README to the best of your knowledge please explain why we are placing the (let fizzBuzz = new FizzBuzz) outside the it block?

# We are declaring the "let fizzBuzz = new FizzBuzz" outside the "it block" because we want to use it for more than one test, so that way we don`t have to repete that code.

#Question 3. In your README to the best of your knowledge please explain the difference between using === and == in JS?

#The operators are equality comparisons, the difference is that, == can compare different data types, and === can only compare the same type of data.

#Question 4. In your README to the best of your knowledge please explain why we are moving (number % 5 === 0) to the top?

#We move (number % 5 === 0) to the top because once the computer finds a true statment, it executes the code and exits the statement.

#Question 5. In your README to the best of your knowledge please explain the difference between feature and unit test

#The unit test runs everything the user can`t see and the feature tests run whats visible to the user, the application.

#Question 6. In your README to the best of your knowledge please explain what expectations in the context of testing are

#Writing expectations are our way of defining our expected output, and guides us in what implementation code to write. Whitout expectation the test will automatically go green.

#Question 7. In your README to the best of your knowledge please write a line to line explanation of what is happening in this code

<!-- <script src="src/js/fizz-buzz.js"></script>                            Using source fizz-buss.js
    <script>
        document.addEventListener('DOMContentLoaded', () => {               Adding listener to page, when loaded....
            let button = document.getElementById('button')                  Saving button element in a varable named 'button'
            let displayDiv = document.getElementById('display_answer')      Saving the div for displaying the output in a varable named 'displayDiv'
            button.addEventListener('click', () =>{                         When user cklicks on button...
                let value = document.getElementById('value').value          Saving a varable named 'value' with user input
                let fizzBuzz = new FizzBuzz                                 Executes method FizzBuzz and save it in a varable named 'fizzbuzz'
                let result = fizzBuzz.check(value)                          Executes method check number and save it in a varable named 'result'          
                displayDiv.innerHTML = result;                              Displays result to user
            })
        })
    </script> -->

#Question 8. In your README to the best of your knowledge please explain what a CDN (Content Delivery Network) is?

# CDN means Contant delivery networks. CDN delivers content to users over networks, and one of it`s greater benefits are the capability to lower the distance between users. Which results in faster delivery of content. That it self also gives me as a user a better experience, which is of importance for the company im visiting/ using content from.

#Author
**Miriam Sallnäs**
