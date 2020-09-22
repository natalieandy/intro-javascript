# Strings

The second primitive data type we'll look at is `string`. This is how JavaScript represents textual data. If it helps, you can think "text" whenever you read "string".

In JavaScript, strings are enclosed in either double quotes `"like this"` or single quotes `'like this, instead'`. There's no difference between the two, but we'll generally prefer single quotes for the sake of consistency.

As with numbers, let's start by playing with strings and building up a reasonable mental model. Type each line that follows into the Node REPL and predict what you'll see once you hit enter.

Make sure you're typing the quotation character `'`.

```javascript
// Prediction: The text entered will be printed (the command 'one' will print "one"). Prediction somewhat correct, although the printed result includes the single quotes rather than omitting them as I had predicted.
'one'
'two'
'three'

'Hello, World!'

//Prediction: this will combine the text together. Not sure what will happen with the quotes. Actual procedure: as I had predicted, the strings combine, but sandwiched by single quotes. Additionally, spaces matter and are not made automatically by the + operator...that is an operator, right?
'Jesse' + ' ' + 'Farmer'
'one' + 'two' + 'three'

//Prediction: I'm at a loss with this one. Actual procedure: the .charAt(x) command seems to identify the x character of a string, starting at 0 instead of 1.
'abcdef'.charAt(0)
'abcdef'.charAt(1)
'abcdef'.charAt(2)
'abcdef'.charAt(3)
'abcdef'.charAt(4)

//Prediction: again, at a loss. Actual Procedure: it looks as though the .padStart and .padEnd commands tell the computer to print what and where. For example, for '==='.padStart(7, '*'), it looks like we're telling the computer to make a string with 7 characters (indicated by the number 7) but to begin that string with the character '*' so that it can create a 7 character string with the characters that are already present (the "===").
'======='
'==='.padStart(7, '*')
'==='.padEnd(7, '*')

//Prediction: the ".toUpperCase()" and ".toLowerCase()" commands will change the text within the string accordingly. Prediction correct.
'this is a sentence'.toUpperCase()
'oNe TwO tHrEe'.toLowerCase()
```

The syntax `'abcdef'.charAt(3)` might be unfamiliar to you. Don't worry if it is — your goal should be to gain a bit of familiarity and start forming tentative ideas about what is going on.

What do you think `charAt`, `padStart`, `padEnd`, etc. are doing?
<!--> Refer to prediction notes above <!-->

## Documentation

If you want to see everything you can do with strings, see MDN's documentation for [String.prototype](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/prototype).
