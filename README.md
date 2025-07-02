# Get multilingual with Lua/Luau
By Issac Bien-Aime


## Introduction
Hello world! If you have experience with JavaScript or Python, Luau may be the next coding language for you.

I have been using Luau for about a month now and I can confidently say its a deep, fun and accessible language, especially for the youth. But what is Luau? Well the language praised for its easy to understand format and similarity to Python, is actually called Lua and was developed in 1993 by professors at the Pontifical Catholic University of Rio de Janeiro. They didn't have access to software outside of Brazil so they instead created they're own. Inspired by Simple Object and data entry languages or SOL's and DEL's Lua went on to be used for things such as games, tools and apps in places big and small.

Luau in specific is a *derivative* of Lua enhanced to work perfectly for the Roblox Studio and Roblox Engine. In this short blog, I'd like to go over some methods and syntax to compare and contrast between JavaScript and Luau.

Heres some data types that JavaScript shares with Luau:
- Numbers
- Booleans (True/False. Luau heavily uses these.)
- Null/Nil (JavaScript uses Null to define an empty value while Luau uses Nil.)
- Strings

Like JavaScript, Luau has comments both multi-line and single.
```js
// This is a single line comment!
console.log("Hello World")
/* This is
a multi-line
comment! */
```

```Luau
-- This is a single line comment!
print("Hello World")
--[[ This is
a multi-line
comment! ]]
```

The main difference being how to begin and end the comments. Note how while the beginning of a multi-line Luau comment goes `--[[` the ending only uses two closing brackets `]]`

I also included how to log/print to the console. JavaScript uses `console.log()` while Luau uses `print()`. Both function exactly the same and can display integers, strings, arrays and more to the output. (Python is most similar to Luau with its `print()` syntax being identical)

Functions in Luau are quite simple like JavaScript:
```luau
function add(a, b)
    return a + b
end
```

```js
function add(a, b) {
    return a + b
}
```
You can almost see `function` and `end` as the curly brackets in way! As with both JavaScript and Luau, you can have anonymous functions or named. Moving on, lets look at an example of a for loop. At the same time we'll go into arrays. (In Luau you create tables which can be used as arrays or dictionaries.)

This for loop will push numbers into an array:
```luau
local numbers = {} --create an empty table
for i = 1, 10 do --for loop
numbers[#numbers+1] = i --push the current number to the array
end
```
```js
lets numbers = [] //create an empty array
for (let i = 1; i >= 10; i++) { //for loop
    numbers.push(i) //push the current number to the array
}
```


If you're interested in exploring Lua or Luau I recommend this [Codecademy Course](<https://www.codecademy.com/enrolled/courses/learn-lua>)!
To get started in Luau you'll need to download the Roblox Studio app on a desktop.


## Core syntax/features. 

* For programming languages: data types, variables, code blocks, functions, conditionals, arrays and objects, and iteration. Include code snippets with explanations.