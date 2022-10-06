# Part II: Foundations of Programming

*Note: Before getting started on these exercises, please be certain that you've read through the root [README.md](../README.md) file in this repository.*

## Exercises

### Basic Requirements

#### Numbers

1. Enter the following expressions into your console.

   ```js
   1 + 2 3
   3 * 5 15
   5 / 4 - 13 -11.75
   5000 * 234  1170000
   1073 / 57 + 200 218.82456140350877
   ```

2. Why are the values produced by the following two expressions different? What
   are they?

   ```js
   3 + 2 * 4 - 1 10
   (3 + 2) * (4 - 1) 15
   ```

3. Calculate 50 years in minutes using the console.
24*60 1440
365*1440 416100
50*416100 20805000
4. What is the percentage of letters in the english alphabet that are vowels (including y)? Use the
   console to find out.
26 % 6 2
5. Try the following expressions in the console:

   ```js
   6 % 2 0
   42 % 10 2
   5 % 2 1
   6 % 3 0
   7 % 4 3
   100 % 12 4
   ```

   What is the significance of the result? How does the `%` (modulus) operator
   work?
is a way to determine the remainder of a division operation
6. Try the following:

   ```js
   3 % 2 1
   4 % 2 0
   5 % 2 1
   6 % 2 0
   ```

   What do the results tell you about the first operand to the modulus operator?
first operand have porsentage of the last module operator
#### Strings

1. Write a string that represents your full name.
var name = "elyesbougamra"
console.log(name)
elyesbougamra
2. Write a string that represents your favorite food.
var food = "pizza"
console.log(food)
pizza
3. Use the `+` operator to combine (known as *concatenation*) two or more
   strings, *e.g.*:

   ```js
   // Your first and last names
   "John" + " " + "Doe"
   ```

   + Your first and last names (as shown above)
   var firstname ="elyes";
   var lastname ="bougamra";
   var lastfirst = lastname + firstname;
   console.log(lastfirst)
   bougamraelyes
   + Your best friend's full name
    var firstname ="zied";
   var lastname ="jlassi";
   var lastfirst = lastname + firstname;
   console.log(lastfirst)
   jlassizied
   + Your home town, state and country
   var home ="cityelkhadhra";
   var state ="tunis";
   var country ="tunis";
   var addr = home + state + country;
   console.log(addr);
   cityelkhadhratunistunis



4. Fix the errors in the following strings:

   ```js
   Where are all the quotes?
   'hmm something is not right"
   'Do other ' * 'operators work with string concatenation?
   ```
   'hmm something is not right"
   "hmm something is not right"
