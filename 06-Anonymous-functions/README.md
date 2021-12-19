---
tutorial: "https://youtu.be/44wVJMqQnUg"
---

# `06` Anonymous functions

An `anonymous function` is a function without a name, for example:

```js
function(param1, param2)
{
    return param1 * param2;
}
```
See how it is missing a name? Probably you are wondering:

 How do I call this function if it doesn't have a name?

`Anonymous function`s need to be stored within a variable in order to be able to use them. For example:

```js
var myFirstVar = function(param1, param2)
{
    return param1 * param2;
}
```
Then, I can call my function like this:
```js
var result = myFirstVar(2,3);
```
## 📝 Instructions:

1. Print on the console, the result of using the function `multy` to calculate the multiplication between `324234` and `47`.