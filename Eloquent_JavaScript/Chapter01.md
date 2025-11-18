# Capítulo 1: VALUES, TYPES AND OPERATORS 
% is used to calculate the modulus. This is just the reminder of a division.
There are three types of special numbers:
- infinite -> Basically "infinito"
- (-) infinite(minus infinite) -> Basically "menos infinito"
- NaN -> when not a number. This occurs when you have an indetermination or when you try to do incoherent arithmetic functions. Basically no es un número

To use string we can use single quotes ('), double quotes (") or backticks (´) but the start and the end must be the same.
\n is interpreted as newline
\t is interpreted as tab character
Bearing in mind this two things, the following string: "This is the first line\nAnd this is the second, \tand this is the second but with a tab before" will see like:
```
This is the first line 
And this is the second,   and this is the second but with a tab before
```
Backtick quotes can do some more tricks than single o double quotes
${} is a template literal and the result will be converted to a string. `half of 100 is ${100/2}` will be `half of 100 is 50`
If we write to backslashes together only one will appear and that is the way to write a string with a backslash inside, for instance `A newline character is weitten like \"\\n\".` and the result is `A newline character is written like "\n"`.

typeoof is used to know the type of the value you give it (string, number...)


