# The `while` and `until` Constructs
 
<img src="https://media.giphy.com/media/D2OI6GvLIn2gM/giphy.gif" width="600px"  hspace="10"> 

## Objectives

1. Build a method that uses `while`
2. Build a method that uses `until`

# Using `while` and `until`

It's our first year at Hogwarts and we're struggling to master the levitation charm, "Wingardium Leviosa". Currently, we have a levitation force of `6`. We need to have a levitation force of `10` in order to actually levitate that feather.

First, we'll write a while loop that will continue to `puts` the phrase "Wingardium Leviosa" while our levitation force is less than `10`. Every time we `puts` that phrase, we should increment our levitation force by `1`.


Then, we'll solve this again by using an `until` loop. It will `puts` the phrase "Wingardium Leviosa" until the levitation force is equal to `10`, incrementing the levitation force by `1` each time we `puts` the phrase.

<img src="https://media.giphy.com/media/yPuurXvMD2wN2/giphy.gif" width="400px" align="right" hspace="10"> 

## Instructions

1. Run the test suite in this lab to get started.

3. Let's get the first test passing by coding our solution in `while.rb`:
Fill out the content of the `using_while` method so that calling it will `puts` the desired phrase while your levitation force is less than `10`. Remember, every time you `puts` the phrase, you should increment your levitation force by `1`.

4. Let's get the second test passing by coding our solution in `until.rb`:
Fill out the content of the `using_until` method to `puts` the desired phrase, "Wingardium Leviosa", until our levitation force equals `10`. Remember, every time you `puts` the phrase, you should increment your levitation force by `1`.

**Hint: If you get stuck an infinite loop when you run your tests or your code, you can abort the test run or code by pressing `CONTROL+C` on your keyboard.**

<p data-visibility='hidden'>KWK-L1 The `while` and `until` Constructs</p>



def Wingardium_Leviosa
  count = 6
  
  while count < 10
    puts "to the right, to the right, to the right, to the right"
    puts "to the left, to the left, to the left, to the   left"
    puts "now kick! now kick! now kick! now kick!"
    puts "now walk it by yourself, now walk it by yourself"
 
 count += 1 
 
 puts "#{count} move(s) completed"
 end
End

