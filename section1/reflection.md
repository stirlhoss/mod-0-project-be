## Section 1 Reflection

1. Regarding the blog posts in Part A, how do you feel about asking questions? Do you tend to ask them too soon, or wait too long, or somewhere in between?
  + I have always been alright with asking questions, but I do tend to wait too long to ask. I, like several of the authors here, want desperately to find the answers to my problems on my own. Sometimes this works out and I end up learning more on the way, but other times I just waste tons of time on something that someone else could answer easily. These blog posts all make a good argument for asking as soon as you are really stuck. There is no need to bang your head into a wall if you don't need to. Even if your question has an obvious answer, it doesn't mean that you are a bad programmer.
2. How would you print the string `"Hello World!"` to the terminal?
  + `puts "Hello World!"`

3. What character is used to indicate comments in a ruby file?
  + #

4. Explain the difference between an integer and a float?
  + A float is just an integer that includes a value after the decimal. Integers are whole numbers.

5. In the space below, create a variable `animal` that holds the string `"zebra"`
  + `animal = "zebra"`

6. How would you print the string `"zebra"` using the variable that you created above?
  + `puts animal`

7. What is interpolation? Use interpolation to print a sentence using the variable `animal`.
  + Interpolation is when you insert a variable or other data into a string.
  + `puts "My favorite animal is a #{animal}!"`

8. What method is used to get input from a user?
  + gets.chomp
  + .chomp is just used to get rid of the input from hitting the enter key. Deletes the `\n`

9. Name and describe two common string methods:
  + `.length` is used to calculate the length of the string you entered
  + `.split` is used to split a string into separate strings for each word. By default it separates these strings by " ", so it will create a new string each time it encounters a space. You can add an argument to change what you are separating with.
