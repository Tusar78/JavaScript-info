## Hello World - Summery

- We can use a `<script>` tag to add javascript code to a page.
- The type and language attribute not required.
- A script in an external file can be inserted with `<script src="./path/app.js"> </script>`.

## Code Structure - Summery
```
alert('Tusar')
alert('Rakibul Islam')
```
> Here, JavaScript interprets the line break as a 'implicit' semicolon, this is called and automated semicolon insertion.

```
alert("Hello")
[1, 2].forEach(alert);
```
> That's because javascript does not assume a before square brackets `[]` So the code is the last example is treated as a single statement. 

## Variable - Summery

> We can declare variables to store data by using the `var`, `let`, or `const` keywords.

- `let` -- is a modern variable declaration.
- `var` -- is an old-school variable declaration.
- `const` -- is like `let`, but the value of the variable can not be changed.

## Number - Summery
- `NaN` -- It represent computational error.
- `Infinity` represent mathematical Infinity. It is a special type of value thats grater than any number.

## BigInt - Summery
- `BigInt` type was recently added to the language to represent integers of arbitrary length.
- A `BigInt` value is created by appending `n` to the end of an integer.

## String - Summery
> A string in JavaScript must be surrounded by quotes.
```
let str = "Hello";
let str2 = 'String quotes are ok too';
let phrase = `can embed another ${str}`;
```
> In JavaScript, there are 3 types of quotes.
- Double quotes.
- Single quotes.
- Backtick.

## Boolean - Summery
- The boolean type has only two values: `true` and `false`
- Boolean value also come as a result of comparisons.

## The “null” value - Summery
- It's just special value which represent "Nothing", "Empty" or "Value unknown".

## The “undefined” value - Summery
- The meaning of `undefined` is "value in not assigned".
- If a variable is declared, but not assigned, then its value is `undefined`.
- Technically, it is possible to explicitly assign `undefined` to a variable
> But we don’t recommend doing that. Normally, one uses `null` to assign an “empty” or “unknown” value to a variable, while `undefined` is reserved as a default initial value for unassigned things.

## Objects and Symbols - Summery
> All other types are called “primitive” because their values can contain only a single thing (be it a string or a number or whatever). In contrast, objects are used to store collections of data and more complex entities.

