# How to think algorithimically

**tldr: Break the problem down and know your tools**

## Tools
### - Loops
- for loops
  - loops through a set number of values i.e 0 to 100
  - used when you KNOW the range of numbers you want to loop through
    - iterating through an array (you know the length of the array)
    - counting up or down i.e 5 to 50
- while loops
  - loops forever until a condition becomes false
  - used when you DON'T know how long its gonna take and want to achieve a set condition
    - i.e creating an integer variable and incrementing it until it reaches 10 
- do-while loops
  - same as while loop but guarantees the code will run at least once
  - doesn't appear that often / in all languages
### - Variables and Objects
- int
  - storing values
  - loop pointers 
- string 
  - usually used only when relevant to the questions
- floats / doubles / etc 
  - usually used only when relevant to the questions
- booleans
  - used for running conditional code or when relevant to the question
  - can be used for breaking a loop
### - Arrays and Hashmaps
- arrays / list
  - stores an ordered group of values
  - often for looping through a set of values (usually for loop used)
- Hashmaps
  - maps a key to a value
  - often used to quickly store values to be easily retrieved later
  
## Approaching a problem
1. understand the problem
   - what are my inputs / what are my outputs
   - come up with example inputs and figure how that will affect the output
   - Are they any edgecases?
2. Figure out your first tool / step
   - Given this question, what is my first step? 
   - What tool should I use ? A loop? What kind of loop?
   - What are the parameters of the tool? What should I name my variables?
3. Figure out the step after that and the one after that...
   - I've figured out my first step, what is the next goal?
   - What tool do I use for my next goal?
   - What are the parameters of the tool? What should I name my variables?
4. Test an example on your code and read through line by line
   - Given [1,2,3] as an input, how does it affect my code?
5. Update until it all works and makes sense

Note: Understanding algorithms takes time and practice. It's ok to not know immediately the best solution to take. 