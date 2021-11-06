# Regex Email Toturtial (replace with your title)

This is an example of email regex.  I will give an example of matching of email letters and characters. When we write [a,b,c,d] this means any of these letters can be used.  When we write [^a,b,c,d] this means any letter but a,b,c,d.  When we write [A-Z] it means any captipal letter from A-Z.  When we write [0-9], it means and number from 0-9.  When we write [^0-9], it means any number except for 0-9. Here is the email that I will do as an example: damali_5@gmail.com. It will be written like this [A-Za-z 0-9 _] +[@] [a-z] +[\a-z]{2,3}
## Summary
I chose emails because emails are something everyone uses in today's society.  Email security is important because most emails contain delicate information.  This information is personal and something that everyone does not need to see.  One of the ways you can keep your emails secured is by using unique passwords and word phrases. Having a difficult password will keep hackers from easily breaking into your emails.

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

In my tutorial, I used anchors, bracket expressions, grouping constructors and character excape.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors - 
An anchor is either a dollar sign or the carrot symbol. If the carot is at the begining it means it will have to match.  If the dollar sign is at the end it means it will have to match at the end
Example of anchors
'Steve is an great coder'
^Steve     coder$

### Quantifiers - 
Quantifiers matches characters in your code. Instead of writing the same thing over and over you can you Quantifiers to match it.  For example, you may want a number to repeat 6 times.  Instead of writing the number 6 times, you can write it like this:
2{0,6}

### Grouping Constructs - 
Grouping constructs matches groups of characters by putting parentheses around the groups to change the outcome.  The parentheses are put around them so you can match the groups.  For example, you can write a list of numbers like this: 3+5+2 but if you group these numbers, the value will be changed: (3 + 5) (2) 

### Bracket Expressions 
 Bracket expressions gives you the option to choose different characters.  When you add anything to the bracket, it means that you can use it.  You can do a letter range like this [a-z] this means that you can use any letter from a-z or you can do a letter range with capital letters like this [A-Z] meaning, you can use anything from A-Z
 if (email.length) matches ("[a-z])
 return true;

### Character Classes  

Character classes are characters written in brackets, it makes a small list of characters match a large list of characters. In regular expressions any character that is used in the bracket will be considered a match. Negated expressions has a carrot in front after the first brackett anything inside of the bracket that is used will not be considered a match. In this example you can use only the letters that are in in brackets.
 const dog = P[err]y

### The OR Operator
The operator expression is used to separate a group. For example, someone could say that they like fall | spring weather, but not winter weather.  You fall and spring would be the operator.

boolen matches
return true ("like fall, spring") && ("not winter")

### Flags 
Flags is a all match phrase. If you have characters that would not normally match, you can select all or dot all to flag it for everything to show.  An example would be suppose you write a word that is in different cases and you want them all to match.  Let's say the word is 'snow'  It is written as snow, SNOW and sNoW.  You can flag this with an i so the word snow will show in any case:
/Snow/i

### Character Escapes 
Character escapes is when a backslash is used in your code.  You could use the backslash to find a list of queries, to match and it can used it to excape letters from a word.  You can match a list of numbers like this:
2+5=7 match = 2\+5=7

## Author

I am a coder who is enjoying coding.  I am learning more everyday to improve my skills and to make myself an amazing developer.  
https://github.com/damiib 
