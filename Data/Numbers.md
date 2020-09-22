# Numbers

JavaScript has a few core data types, which is calls "primitive" types. The first we'll deal with is `number`.

Open up a terminal and run the `node` command to get a node prompt.
<!-->What does node mean? Like what does it refer to? What is it in the grand scheme of things? <!-->
Type — **don't copy!** — each of these lines one by one. Before you hit enter, make a prediction about what you'll see on the screen. Were your predictions correct?

<!-->The following equations were completed using the node prompt in the terminal, so I did not include the answers here. <!-->

```javascript
//Prediction: they will "combine" normally through addition. Predicition Correct.
1 + 2
3 + 4

//Prediction: they will act normally through subtraction. Predicition Correct.
1 - 2
2 - 1

//Prediction: these will act as the ones above. Prediction correct.
14 + 192
99.5 + 100.5
```

Try some examples on your own. See if you can't find anything surprising.

Again, type each line below, make a prediction about what you'll see, and hit enter. In code, we denote multiplication with `*` and division with `/`.

```javascript
//Prediction: they will act normally through multiplication. Prediction correct.
1 * 2
2 * 10
15.5 * 4

//Prediction: they will act normally using division. Predicition correct.
8 / 2
10 / 2
10 / 3

5 / 2
2 / 5
```

## Extra Numerical Operations

Here are two operations that might not be obvious at first glance. See if you can't figure out what they do. Play around with different values.

The first operation is `**`:

```javascript
//Prediction: it will function as follows: 10*2=20, 20*2=40. Actual procedure: the '**' operation means x 'to the power of x.'
10**1
10**2
10**3
10**4

2**2
2**3
2**4
```

The second operation is `%`:

```javascript
//Prediction: what percentage of x exists in y? Actual procedure, copied from my Codecademy notes: "functions to return the number that remains after the right-hand number divides into the left-hand number as many times as it evenly can."

5 % 2
5 % 3
5 % 4
5 % 5

10 % 2
10 % 3
10 % 4
10 % 5

20 % 18
```

What might `%` be doing? What happens if you use negative numbers?
<!--> Negative numbers seem to make the "equation" equal 0. <!-->

## Documentation

See the MDN page on [Arithmetic operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators) for more.
