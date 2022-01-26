# Ruby Exercises - Part 1

## READ BEFORE STARTING

**Use Git or GitHub Desktop to push this exercise to GitHub** <br>

**Use a cloud based service or an IDE**<br>

**You can use one project for all exercises**<br>

**Exercise 0: Setup** 
- Create a folder called Code-Labs-Ruby-Exercises. Publish this to GitHub and name the repo `Code-Labs-Ruby-Exercises`. Create four separate folders: part-1-exercises, part-2-exercises, part-3-exercises, part-4-exercises.
- Create a **README.md** file at the root directory. In your README.md file. Copy and paste the following: 

``` 
# Ruby Exercises and Terminology 

Here is a list of ruby terms and definitions used in class.

## Part 1 
<em>**Layer of Abstraction**</em> - INSERT DEFINITION HERE
<em>**Data Type**</em> - INSERT DEFINITION HERE
<em>**Variable**</em> - INSERT DEFINITION HERE
<em>**Constant Variable**</em> - INSERT DEFINITION HERE
<em>**Method**</em> - INSERT DEFINITION HERE
<em>**IRB**</em> - INSERT DEFINITION HERE
<em>**Operators**</em> - INSERT DEFINITION HERE

## Part 2

## Part 3

## Part 4
```

- replace each <em>INSERT DEFINITION HERE</em> with the correct definition. <br>
**Exercise 1.1: Print to the console**

- Use the keyword p to print out the string `p` to the console
- Use the keyword puts to print out the string `puts` to the console
- Use the key word print to print out the string `print` to the console
- Create a local variable called my_name and set it to your name. Print it to the console.
- Create a variable called beginning_sentence and set it to `"My name is "`. Create another variable called full_sentence and set it equal to the combination of both beginning_sentence and my_name. Use the + operator to do that. Print full_sentence and you should get `My name is German` in the console.

**Exercise 1.2: Define a method**

- Define a method called say_hello_to. When you call the method, you should be able to see `Hello, John Doe!` in the console.
- Add a parameter called name to the method you just created. Use the parameter to print out `Hello, ` follow by the parameter name. Call the method and add the my_name variable as an argument.
  - Result: `Hello, German!`

**Exercise 1.3: Define a method with multiple arguments**

- Define a method called names_of_my_pets. Add three parameters to the method: name_1, name_2, name_3.
- Create three variables that correspond to the parameters of your method. Set them to whatever value you like.
- When calling the method, be should to add your variables as arguments and you should get something along the lines of `I have 3 pets! Their names are Apollo, Athena and Loki!` in the console.

**Exercise 1.4: Use built in string methods**

- Create a variable named sentence and set it to `Hello John Doe!`. Use the build in sub method to replace `Hello` with `Hi`. Print out the result. You should get `Hi John Doe!` in the console.
- Create a variable called solution and set it to `Hi John Doe!`. Use the built in match? method to check your output from the previous problem (see example of match?). Print the result and you should get `true` in the console.

Example:

```ruby
name = "John"
puts name.match?("Amy")
# false
```

**Exercise 1.5: Use escaping to output single quotes in a string**

- Output `'Single Quotes'` to the console (hint: use backslashes)

**Exercise 1.6: Print out user input**

- Use `gets.chomp`. To get the user input, then store it in a variable called user_input. Print onto the console "You typed: " follow by what the user entered.

NOTE: You can comment out this code to prevent you from always having to get user input

- Define a method named multiply_by_two with one parameter. Get the user input and use the method you defined to multiply that number by 2. Print the result.
- Define a method named divide_by_two with one parameter. Take in a user input and store and divide that value by two using divided_by_two. Print the result.

If user entered 5, result should be 2.5.