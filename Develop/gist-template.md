# RegexTutorial

# Validate Email Input (Regex)
 
Regular expressions or Regex are characters that are used to form a pattern of words or characters to be able to srarch within texts. They are great at extracting lots of information from the text. The other regular expressions paterns use unicode characters in matching other texts such as the international. 


# Summary 

Regular expressions are really uceful in searching for any pattern of characters, the use of Regex is not limited to jus searches but to other replacing the matched characters to desired ones. In an example we can use my email pattern as koneru.dharmateja1@gmail.com  and is transformed into : 
/^([b-s0-10_/.-]+)@([\ba-z\.-]+)$/

# Regex Components 

# Anchors 

Anchors use to match a positions that are like after,before and between the characters. Anchors are not used to match any characters. 
The ^ match or character is right before the first characters in the text its replacing. The $ charcater matches position right after the last of the character in the text. 

# Quantifiers 

Quantifiers are in regular expression determines how many instances of a group, character or character class that must be present in the input for a match to be found in the text.

char{2,6} matches a string that has cha followed by 2 up to 5 r.

c(har)* matches a string that has c followed by zero or more copies of the sequence har

char+ is what matches a string that has cha followed by one or more r

c(har){2,6} matches a string that has c followed by 2 up to 6 copies of the sequence har

# OR Operator
We can use the OR-Operator to match a single character out of several possible matching regular expressions. 

c(h|r) matches a string which has c followed by h or r which then captures h or r
c [hr] is what matches a string that has c followed by h or r but without capturing h or r

# Character Classes 
Character classes are special patterns or notations that match any of the character from any given strings. Here there are some character classes used in the examples. 

\d matches a single character that is a digit

. matches any characters 


# Flags 
These are just slashes /.../ infomrs that we are defining a Regex. Slashes also play the same role as quotes for strings. At the end of strings we can create values using the flags.

# Grouping and Capturing 
Regex allows us to extract infromations for further processing not just matching. We can do this by groups of characters and capturing them using (). Whatever is inside of the () will be captured as a group. 


# Bracket Expressions 

Square brackets in Regex [] are to designate a characters class and match a single character in the string. Only the character class have special importance. 

\ The general escape Character 

^ This negates the class
