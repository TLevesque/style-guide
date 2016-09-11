# Codeworks coding style guide

This is a reference to the style conventions that we use at Codeworks.

## General

Set up your code editor to:

- Indent with 2 spaces.
- Use only spaces for indentation (no tabs).
- Avoid trailing whitespaces.

Then make sure to respect correct indentation.

## HTML

- Write classes and ids in lowercase, separating words with dashes.
```html
<div class="my-class" id="my-id"></div>
```

## JavaScript

- Put semi-colons at the end of your statements.
```js
// Good
var letter = 'a';

// Bad
var letter = 'a'
```
- Assign each variable on a separate line.
```js
// Good
var letter = 'a';
var number = 1;

// Bad
var letter = 'a', number = 1;
var letter = 'a',
    number = 1;
```
- Use "camel case" for variables naming (if it's for a class the first letter is uppercase). 
```js
// Good
var myBoolean = true;
function MyClass (name) {
  this.name = name;
}

// Bad
var myboolean = true;
```
- Be descriptive with your variable names.
```js
// Good
var numberOfStudents = 100;

// Bad
var nos = 100;
```
- Use function declarations, not expressions.
```js
// Good
function hello () {
  console.log('hello');
}

// Bad
var hello = function () {
  console.log('hello');
};
```
- Use single quotes for strings.
```js
// Good
var myString = 'Hello world';

// Bad
var myString = "Hello world";
```
