javascript-roadtrip
===================

Code School - JavaScript Road Trip helps you learn the basics of the JavaScript language

### Level 1 - The Cliffs of Value

#### Basic Operations
As any other language JavaScript has arithmetic operators. They are, as you can imagine, used to perform arithmetic between variables and/or values.

| Operator |	Description     |	Example |	Result |
| -------- | :--------------: | :-----: | ----:  |
| +        |	Addition        |	3 + 2   |	5      |
| -        |	Subtraction     |	3 - 2   |	1      |
| *        |	Multiplication  |	3 * 2   |	6      |
| /        |	Division        |	3 / 2   |	1.5    |
| %        |	Modulus         |	3 % 2   |	1      |


#### Strings
Are the JavaScript way to handle, stores and process flat text. In order to signal to JavaScript that we want to process some flat text, we normally use a pair of quotations mark surrounding some text.

```js
  var text = "Raindrops Keep Falling";
  console.log(text);
```
We can also use the addition(+) operator with strings, or string with numbers and expressions in a process called concatanation. Concatanation place strings together in one string.

```js
  var text = "Raindrops Keep Falling";
  var text2 = "On My Head";
  console.log(text + text2);
```
Once we can need some quotations marks to be scaped, or even the backslash, we can use the characters need backlash. 

```js
  var text = "Raindrops Keep Falling \t ops";
  var text = "Raindrops Keep Falling \" ops";
```

Sometimes is also important to compare two or more strings. For that, javascript allow us to do that, in different forms, using the equal(=) operator.

| Operator | Description | Example      | Result |
| -------- | :---------: | :----------: | -----: |
| ==	   | Exact equal | "a" == "a"   | true   |
| ==	   | Exact equal | "a" == "A"   | false  |
| !=       | Different   | "a" != "a"   | false  |
| !=       | Different   | "a" != "A"   | true   |

The String object has some properties and methods that could be helpull sometimes.

| Property | Description          | Example      | Result |
| -------- | :------------------: | :----------: | -----: |
| length   | return string length | "abc".length | 3      |


