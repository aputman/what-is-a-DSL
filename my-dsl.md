# Language
Alda
[Source Code](https://github.com/alda-lang/alda)


# Domain
General Light-weight Music Programming Language


# Computational model
When someone runs an alda script, their code is first converted into Clojure
code which creates a map of the score. That is then used to produce sounds 
that the alda code described. 

# DSL-ness
Alda is purely domain-specific. It only allows for the description of different 
lines of music. There are no loops or conditionals, so the language is not
turing complete. There is no computation that can be done with the language
other than playing static lines of music. 

# Internal or external?
This is an external DSL. While it is eventually converted into Clojure code
it starts off as just a list of lines and list of notes. It is then parsed
and converted into other code. 

# Host language
Clojure


# Benefits
It allows for easier and quicker sketching of musical ideas than existing 
music notation tools. Editing and addition to existing ideas is also much
simpler as it doesn't require hard to navigate menus. 


# Drawbacks
Using this instead of a GUI music notation tool limits the type of people
who can review and understand the worked created. Installing the program
and even writing scripts requires a limited ammount of computer and 
programming knowledge.
