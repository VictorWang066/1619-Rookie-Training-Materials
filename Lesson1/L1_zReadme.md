Hello robotics peers, in this section, we will learn about the following things:
    1. What is Java, and how does it work?
    2. What are Variables and how do you use it?
This README document, like all the other ones, will walk you through the context
of everything we do, as well as how to do it. You will also in multiple occurances be 
redirected to the Java files above to actually write some code. In accordance to that,
this document will be sectioned by their corresponding Java documents

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
    If you just type a line of text, how would your code know if it's code or the text you want to print?
Especially since words not recognized as code will result in errors. Well, text need to be surrounded 
by sets of double parenthesis (""), thus, when the code reads these parenthesis, they will understand 
that whatever is within them should be read as text and not code.
    The second part is that your code needs to know when to stop reading each line of your command, think
of it like the commas at the end of each sentence. How Java does this is through semi-colons(;), for our
purposes, just remember to add semi-colons at the end of each line.

