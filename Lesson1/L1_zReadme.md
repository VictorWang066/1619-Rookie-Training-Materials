Hello robotics peers, in this section, we will learn about the following things:
    1. What is Java, and how does it work?
    2. What are Variables and how do you use it?
This README document, like all the other ones, will walk you through the context
of everything we do, as well as how to do it. You will also in multiple occurances be 
redirected to the Java files above to actually write some code. In accordance to that,
this document will be sectioned by their corresponding Java documents
(If you're ever stuck, type "git checkout references" to check the answers, and check back
to this document with "git checkout main" after you're done)

Then, without furthur adue, let's get into it! 

------------------------------------------------------------------------------------------------

SECTION 0 - So, How does this programming thing work? 

    Picture that you now have a robot, and you need to command it to do something. How should
you do that? Well, you can't just write in you're code "drive forward and pick up that ball"
because the robot don't speak english. In fact, the only thing the robot can understand is 
binary -- sequences of ones (on) and zeros (off) that, under specific patterns, turn out to 
become commands that it can understand (for reference, if you happen to know what morse code is, 
that is a type of binary "language")
    But don't worry, we don't actually have to write in these ones and zeros. Instead, people have
developed "programming languages" such as Java, Python, or C++, these languages connect specific
phrases (what we call "syntax") to certain logic or action, so that when you type up these
syntax, the robot would still be able to understand what you are talking about.
    However, this approach does lead to one problem -- the creators of these programming languages
linked syntax to function in a 1 to 1 basis, which means the computer would only understand you if
you type the EXACT syntax. If you don't, there will likely be an error message. Take a minute to
let that sink in, or not, because throughout your programming career you would definetly feel it's 
impact

------------------------------------------------------------------------------------------------

SECTION 1 - Hello World -- Printing your first line

    In accordance to the conventions, the first line we write would be printing the phrase 
"Hello World". To do that, we will use the command "System.out.println()", which prints whatever is
between the parenthesis on to the terminal. However, there is a catch (well actually there's two).
    If you just type a line of text, how would your code know if it's code or the text you want to 
print? Especially since words not recognized as code will result in errors. Well, text need to be 
surrounded by sets of double parenthesis (""), thus, when the code reads these parenthesis, they will 
understand that whatever is within them should be read as text and not code.
    The second part is that your code needs to know when to stop reading each line of your command, think
of it like the commas at the end of each sentence. How Java does this is through semi-colons(;), for our
purposes, just remember to add semi-colons at the end of each line.

    Now you've learned everything, move on to "L1_HelloWorld.java" and complete the practices there

------------------------------------------------------------------------------------------------

SECTION 2 - Variables

    Let's imagine another senario, say you have the number 18, and you want to use it to represent 
someone's age. Just puting the number 18 in the code is not very descriptive, fortunately though, we 
can represent it with text. This is where variables comes in, just like how you can represent a number
with "x" or "y" in math, you can store numbers (as well as almost everything else) in a variable in 
programming.
    To do that, you would use the syntax "datatype name = value", so if you are trying to store our 
number "18" with the name "age", you would write "int age = 18;" (don't forget the semi-colone). And 
you may ask "what's this 'datatype' doing here?", well, in order to save memory space, Java stores 
different types of variables differently, since a number is really easy to represent using binary, but
something like a sentance would be way more difficult to store. Thus, as you declare the existance of 
these variables, you need to mark them with different identifiers, so that Java understands how to
properly deal with your variable.
    The variable types important to us right now are:
    - String: used to store sentances and phrases (that are within a paires of parenthesis)
    - int: used to store an integer, or whole number
    - double: used to store fractions and decimal numbers
    - boolean: used to store a "true or false" value
    And lastly, there is the "var" keyword, which adapts to the datatype you assign to it. We do not 
    recommend using it, however, since it makes code less understandable by others.
    One final thing, just like you are able to change the things you store in a cabinet, you can change
the values stored in variables. And, as you've already defined what type of variables would be stored,
you only need to use the name of the variable when changing the value inside it. For example, if I want
to change the number in my "age" variable defined above, I just have to write "age = 19". In fact, 
because writing out the datatype means declaring a new variable to the code, if you did put "int" infront,
you would have made another "age" variable, instead of changing the original one. (Also because of this,
"var" would only adapt once, so you can't make a type "var" variable that used to house a integer to a 
string value, for example)

    Now you've learned everything, move on to "L1_HelloWorld.java" and complete the practices there

------------------------------------------------------------------------------------------------


