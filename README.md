# RegEx
A brief Regular Expression tutorial, walkthrough, and explaination of how it works.

Summary
This code here /^#?([a-f0-9]{6}|[a-f0-9]{3})$/ is what is known as a regular expression, often reffered to as RegEx as well. A regular expression is a string of characters that is used to pattern match text. This example is used to find color hex values and it will be referred to throughout this tutorial. To start off, a regular expression is considered a literal, so it must be wrapped / In back-slashes like this /. The components inside serve important functions which will be explained below.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors

^ and $ are both RegEx anchors.

^ signifies that the string begins with the string or expression that immediately follows this anchor. 
In this example, /^#?([a-f0-9]{6}|[a-f0-9]{3})$/ we are trying to find a hex code, and hex codes always begin with #. This anchor can also be used to find ranges of characters in bracket notation if an expression doesn't always begin with the same thing. 
<br>
/$ signifies the end to a string or expression. It can also just be thought of as a closing tag to an html element that closes the regular expression. 


### Quantifiers
quantifiers are used to set further specific requirements that the string must match. They use the curly braces {} which include a number or two. They require a match to be met a specific number of times of in a range. In our hex code example, this is the body ([a-f0-9]{6}|[a-f0-9]{3}) these operators are saying that this expression must be repeated six times or 3 times. 

### OR Operator
Reffering right back to the example in the quantifiers section above ([a-f0-9]{6}|[a-f0-9]{3}) this expression uses the or operator. | is the or operator which is used to say that it must meet this requirement or this other requirement. In our example, Hex codes are always either 6 digits or 3 digits long, so the or operator must be used to find both cases. 

### Character Classes
Character classes are a set of characters that can occur in an input string to fulfil a match. In this example: [a-f0-9] its saying that this can be a letter between a and f or a number between 0 and 9. 
### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind



## Author
A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
