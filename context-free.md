# Context Free

##  Who is this programming language for?
People who want to create semi-randomly drawn art.

## What is easy to do in this language? Why is it easy?
It is easy to create any number of paintings from the same code. This is easy 
because the DSL has you define small interchangable components that will be
combined together randomly by the interpreter. 

## What is hard to do in this language? Why is it hard?
It is hard to draw a specific static painting. This is hard because the scale
and position in the painting isn't always well defined. This is because it 
is designed to scale with the number of painting components being used, not
for a static painting. 

## How did you learn how to program in this language?
It was actually difficult to start but I learned by looking at samples given
by the application.

## What is the underlying _computational model_ for this programming language? 
From what I can tell, the program runs like any other language with rules 
being the functions. When a rule is called with a certain parameter, those
parameters are implemented until that rule is done being run. Everytime a 
the x and y parameters expand past what is currently available, the picture 
expands. When there are multiple definitions for a rule, the one that is used
is randomly chosen each time the rule is called.


## What do you think is interesting about the ContextFree program you wrote?
I think it is interesting how it can return such a simple and plain picture 
and also one that has hundreds of circles. It is simple but it shows the 
variety that can come from the DSL. 
